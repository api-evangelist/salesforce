---
name: salesforce-composite-write
description: Create a parent record and its related children in one Salesforce request, chaining dependent IDs with reference IDs instead of round-tripping.
generated: '2026-08-13'
method: generated
source: openapi/salesforce-composite-api-openapi.yml, openapi/salesforce-trees-api-openapi.yml, openapi/salesforce-collections-api-openapi.yml, conventions/salesforce-conventions.yml
api: Salesforce Composite API
base_url: https://{instance}.salesforce.com/services/data/v{version}/composite
operations:
  - Composite
  - CompositeBatch
  - CompositeGraph
  - SObjectTree
  - SObjectCollectionsCreate
  - SObjectCollectionsUpsert
---

# Write a related record graph in one call

Naively creating an Account, then a Contact pointing at it, then an Opportunity pointing at both,
costs three round trips and three slots of your daily API allocation — and leaves orphans if the
second call fails. The Composite family fixes all three problems.

## Choosing the right composite resource

| You want | Use | Operation |
|---|---|---|
| Dependent writes where later calls need earlier IDs | Composite | `Composite` |
| Independent calls batched for quota, no chaining | Composite Batch | `CompositeBatch` |
| Multiple independent subgraphs, each all-or-none | Composite Graph | `CompositeGraph` |
| One parent with nested children of known shape | sObject Tree | `SObjectTree` |
| Up to 200 records of the same object | sObject Collections | `SObjectCollectionsCreate` |

All of them count as **one** API request against the org allocation regardless of how many
subrequests they contain. That is the main reason to use them.

## Steps (the dependent-chain case)

1. **Build the subrequest list** — `POST /services/data/v{version}/composite` with
   `{"allOrNone": true, "compositeRequest": [ ... ]}`. Each entry needs `method`, `url`,
   `referenceId`, and a `body` for writes. Keep `url` version-consistent with the outer path.

2. **Chain with reference IDs.** Give the parent a `referenceId` such as `NewAccount`, then in a
   later subrequest write `"AccountId": "@{NewAccount.id}"`. Salesforce substitutes the real ID at
   execution time. This is the whole point — you never see the intermediate ID.

3. **Set `allOrNone` deliberately.**
   - `true` — any subrequest failure rolls the entire composite back. Use this for a record graph
     that is meaningless half-written.
   - `false` — successful subrequests commit and failed ones do not. Use this only when the
     subrequests really are independent.

4. **Read every subresponse.** The outer call returns `200` even when subrequests failed. Iterate
   `compositeResponse[]` and check each `httpStatusCode` and `referenceId`. **An HTTP 200 on the
   composite does not mean your writes succeeded.**

## Rules that will bite you

- **The outer 200 lies.** This is the single most common composite bug. Always inspect the
  per-subrequest status codes.
- **Limits:** Composite allows up to 25 subrequests (of which at most 5 may be query-type calls
  that return more than 2,000 rows). Composite Batch allows 25. sObject Collections allows 200
  records. Exceeding these is a request-level `400`, not a partial success.
- **Composite is not idempotent.** A retried composite that contains `POST` creates duplicates.
  Where you can, make the subrequests `PATCH` upserts on an External Id field — see
  `skills/salesforce-upsert-by-external-id.md`. That converts the whole graph into a safely
  retryable operation, which is as close to an idempotency key as this platform gets.
- **Reference IDs are scoped to a single request** and must be unique within it. They are not
  persisted and cannot be referenced from a later call.
- **Failed subrequests report `PROCESSING_HALTED`** for everything after the failure when
  `allOrNone` is `true`. The real cause is the first non-2xx entry — read that one, not the
  cascade behind it.
- Errors keep the standard array shape: `[{"message", "errorCode", "fields"}]`.
