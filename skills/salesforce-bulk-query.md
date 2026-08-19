---
name: salesforce-bulk-query
description: Extract a large Salesforce result set with a Bulk API 2.0 query job instead of burning REST quota on paged SOQL.
generated: '2026-08-13'
method: generated
source: openapi/salesforce-query-jobs-api-openapi.yml, openapi/salesforce-info-api-openapi.yml, openapi/salesforce-get-api-openapi.yml, openapi/salesforce-abort-api-openapi.yml
api: Salesforce Bulk API 2.0
base_url: https://{instance}.salesforce.com/services/data/v{version}/jobs/query
operations:
  - createQueryJob
  - GetJobInfoQuery
  - GetJobQueryResult
  - AbortaJobQuery
  - GetAllQueryJobs
---

# Extract a large result set with Bulk API 2.0

Use this instead of paged SOQL whenever the result set is large (Salesforce's own guidance is
roughly >2,000 records). A whole Bulk job costs a handful of API calls; the same extract over
`executeQuery` costs one call per 2,000-row page and will eat the org's daily allocation.

## Before you start

- OAuth bearer token with the `api` scope.
- Results come back as **CSV**, not JSON. Plan for that.
- Bulk 2.0 is asynchronous. There is no synchronous mode; if you need the answer inside one
  request/response cycle, use `salesforce-soql-query` instead.

## Steps

1. **Create the job** — call `createQueryJob`:
   `POST /services/data/v{version}/jobs/query`
   with `{"operation": "query", "query": "<SOQL>"}`. Use `"queryAll"` as the operation if you need
   deleted and archived rows. The response carries the job `id` and `state: UploadComplete`.

2. **Poll for completion** — call `GetJobInfoQuery`:
   `GET /services/data/v{version}/jobs/query/{jobId}`
   Poll on a backoff, not a tight loop. Terminal states are:
   - `JobComplete` — results are ready.
   - `Failed` — read `errorMessage`. Do not retry blindly; a malformed query fails the same way
     every time.
   - `Aborted` — someone (possibly you) cancelled it.

3. **Fetch the results** — call `GetJobQueryResult`:
   `GET /services/data/v{version}/jobs/query/{jobId}/results?maxRecords={n}`
   The response body is CSV. **Paging here is header-driven**: read the `Sforce-Locator` response
   header and pass it back as the `locator` query parameter on the next call. Keep going until
   `Sforce-Locator` comes back as `null`. This is a different pagination mechanism from the REST
   API's `nextRecordsUrl` — do not confuse the two.

4. **Abort if you must** — call `AbortaJobQuery`
   (`PATCH /services/data/v{version}/jobs/query/{jobId}` with `{"state": "Aborted"}`) to stop a
   runaway job. An abandoned job still consumes org resources until it finishes.

## Rules that will bite you

- **`Sforce-Locator: null` is the terminator**, and it arrives as the literal string `null` in a
  header. Treat a missing header and a `null` header the same way: stop.
- **`maxRecords` is a hint.** Salesforce may return fewer rows than you asked for and still hand
  you a locator. Never infer "done" from a short page.
- **CSV encoding matters.** The default `lineEnding` is `LF`; set it to `CRLF` at job creation if
  your consumer needs it. Column order follows the SOQL SELECT list.
- **Errors are the standard array shape** — `[{"message", "errorCode", "fields"}]` — see
  `errors/salesforce-error-codes.yml`.
- **Job creation is not idempotent.** Retrying step 1 after a timeout creates a second job. Call
  `GetAllQueryJobs` (`GET /services/data/v{version}/jobs/query`) to check for an in-flight job
  before creating another one.
- **Bulk has its own limits** separate from the REST allocation — batches per day and concurrent
  jobs. See `rate-limits/salesforce-rate-limits.yml`.
