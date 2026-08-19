---
name: salesforce-soql-query
description: Run a SOQL query against a Salesforce org over the REST API and page through every result row.
generated: '2026-08-13'
method: generated
source: openapi/salesforce-query-api-openapi.yml, openapi/salesforce-data-api-openapi.yml, conventions/salesforce-conventions.yml
api: Salesforce REST API
base_url: https://{instance}.salesforce.com/services/data/v{version}
operations:
  - executeQuery
  - QueryAll
  - listApiVersions
---

# Query Salesforce records with SOQL

Use this when you need CRM records out of a Salesforce org and you can express the selection as
SOQL. This is the read path — for writes see `salesforce-upsert-by-external-id`, and for anything
over ~2,000 records see `salesforce-bulk-query`.

## Before you start

- You need an OAuth 2.0 bearer token. Send it as `Authorization: Bearer <access_token>` on every
  request. See `authentication/salesforce-authentication.yml` and `scopes/salesforce-scopes.yml`
  — the `api` scope is the one that gates this surface.
- `{instance}` is the org's My Domain host, not a fixed Salesforce hostname. It comes back in the
  `instance_url` field of the token response. Do not hardcode `login.salesforce.com`.
- Pick a version. `listApiVersions` (`GET /services/data/`) is **unauthenticated** and returns the
  list of supported `vNN.0` versions. Current is v67.0 (Summer '26). See
  `lifecycle/salesforce-lifecycle.yml`.

## Steps

1. **Resolve the API version** — call `listApiVersions` (`GET /services/data/`) and take the
   highest `version` you are prepared to support. Salesforce keeps old versions alive for years,
   so pinning is safe; drifting to "latest" is not.

2. **Run the query** — call `executeQuery`:
   `GET /services/data/v{version}/query?q={urlencoded SOQL}`
   Always name the fields explicitly. SOQL has no `SELECT *` and Salesforce has no sparse-fieldset
   query parameter, so the field list in the query *is* your projection.

3. **Page until done** — the response envelope is
   `{totalSize, done, nextRecordsUrl, records[]}`. If `done` is `false`, issue a `GET` against the
   **absolute path** in `nextRecordsUrl` and concatenate `records`. Repeat until `done` is `true`.
   Do not try to construct the cursor yourself; it is opaque.

4. **Include deleted or archived rows only if you mean it** — `QueryAll`
   (`GET /services/data/v{version}/queryAll`) takes the same `q` parameter but also returns rows in
   the Recycle Bin and archived activity records. Use it for reconciliation and sync, not for
   normal reads.

## Rules that will bite you

- **Errors are an array, not an object.** A failure returns
  `[{"message": "...", "errorCode": "...", "fields": [...]}]`. Read `errorCode`, not the HTTP
  status alone. See `errors/salesforce-error-codes.yml`.
- **`MALFORMED_QUERY` is a 400 and is your fault** — usually an unqueryable field or a bad
  relationship path. Call `SObjectDescribe` first if you are building the query dynamically.
- **Watch the org's daily allocation.** Every call counts against a rolling 24-hour org-wide
  quota. Read the `Sforce-Limit-Info` response header on every response — it reports
  `api-usage=<used>/<total>` — and back off before you exhaust it. Exceeding it returns
  `REQUEST_LIMIT_EXCEEDED`. See `rate-limits/salesforce-rate-limits.yml`.
- **There is no idempotency key on this API.** Reads are safe to retry; writes are not (see the
  upsert skill for the one idempotent write path Salesforce does offer).
- **Long queries count against concurrency.** Requests running longer than 20 seconds are capped
  at 25 concurrent per production org (5 in Developer/Trial). A slow query storm will surface as
  `REQUEST_LIMIT_EXCEEDED` even when your daily quota is fine.
