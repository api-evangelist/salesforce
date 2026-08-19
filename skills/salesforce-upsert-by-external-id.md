---
name: salesforce-upsert-by-external-id
description: Idempotently create-or-update a Salesforce record keyed on your own external system's ID, without duplicating rows on retry.
generated: '2026-08-13'
method: generated
source: openapi/salesforce-external-api-openapi.yml, openapi/salesforce-describe-api-openapi.yml, conventions/salesforce-conventions.yml
api: Salesforce REST API
base_url: https://{instance}.salesforce.com/services/data/v{version}
operations:
  - SObjectRowsbyExternalID
  - SObjectDescribe
  - SObjectRows
  - SObjectCreate
---

# Upsert a Salesforce record by external ID

This is **the** idempotent write path on the Salesforce platform. Salesforce publishes no generic
`Idempotency-Key` header — see `conventions/salesforce-conventions.yml`, where `idempotency.header`
is explicitly `null`. Upsert on an External Id field is the substitute, and it is the pattern you
should reach for any time a write might be retried.

## Before you start

- The target object needs a **custom field marked External Id** (and ideally Unique). You cannot
  upsert against an arbitrary field. Confirm it with `SObjectDescribe`
  (`GET /services/data/v{version}/sobjects/{SObject}/describe`) and look for
  `"externalId": true` on the field.
- OAuth bearer token with the `api` scope, as always.

## Steps

1. **Confirm the External Id field exists** — call `SObjectDescribe` on the object once and cache
   it. Look for a field where `externalId` is `true` and `unique` is `true`. If it is not unique,
   a duplicate match returns an error rather than picking one, which is the correct behaviour but
   surprises people.

2. **Upsert** — call `SObjectRowsbyExternalID`:
   `PATCH /services/data/v{version}/sobjects/{SObject}/{ExternalIdField}/{value}`
   with the record body as JSON. Do **not** include the External Id field in the body as well as
   the URL unless the values match — Salesforce rejects the mismatch.

3. **Read the outcome from the status code, not the body.**
   - `201 Created` — no record matched; a new one was inserted. Body carries `{id, success, errors}`.
   - `204 No Content` — a record matched and was updated. **There is no body.** Do not try to parse
     one.
   - `300 Multiple Choices` — more than one record matched that External Id value. The body is an
     array of matching record URLs. This means your External Id is not unique; fix the data, do not
     retry.

4. **Retry safely.** Because the key is in the URL and the semantics are match-or-insert, replaying
   the exact same `PATCH` after a timeout or a 5xx cannot create a second row. This is the only
   place in the core platform API where that is true.

## Rules that will bite you

- **`POST` to `SObjectCreate` is NOT idempotent.** A retried create makes a second record. If you
  are writing from a queue or any at-least-once delivery path, use this skill instead.
- **Errors are an array**: `[{"message", "errorCode", "fields"}]`. `DUPLICATE_VALUE` and
  `INVALID_FIELD_FOR_INSERT_UPDATE` are the two you will hit most.
- **This is one API call per record.** For bulk loads use
  `SObjectCollectionsUpsert` (up to 200 records per call, also keyed on External Id) or the
  Bulk API 2.0 ingest job — see `skills/salesforce-bulk-query.md` for the job lifecycle shape.
- **Field-level security still applies.** A field the connected app's user cannot write is silently
  dropped on update and rejected on insert. Describe reflects the *calling user's* permissions,
  which is why you should not cache it across users.
- **Every call counts** against the rolling 24-hour org allocation; check `Sforce-Limit-Info`.
