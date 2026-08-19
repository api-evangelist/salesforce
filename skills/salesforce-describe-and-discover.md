---
name: salesforce-describe-and-discover
description: Discover what a Salesforce org actually contains — supported API versions, available objects, and a single object's fields — before writing any query or write.
generated: '2026-08-13'
method: generated
source: openapi/salesforce-versions-api-openapi.yml, openapi/salesforce-describe-api-openapi.yml, openapi/salesforce-limits-api-openapi.yml, data-model/salesforce-data-model.yml
api: Salesforce REST API
base_url: https://{instance}.salesforce.com/services/data
operations:
  - listApiVersions
  - DescribeGlobal
  - SObjectDescribe
  - SObjectBasicInformation
  - getOrgLimits
---

# Discover a Salesforce org before you call it

Every Salesforce org is a different API. Custom objects, custom fields, field-level security and
installed managed packages all change the surface, so the shape you get is org-specific and
user-specific. Run this discovery pass first; do not assume the standard object model.

## Steps

1. **List supported API versions** — `listApiVersions`, `GET /services/data/`.
   This is **unauthenticated**, which makes it the cheapest reachability check you have. It returns
   `[{label, url, version}]`. Pick a version and pin it. Current is v67.0 (Summer '26); Salesforce
   ships three seasonal releases a year and retires only very old versions. See
   `lifecycle/salesforce-lifecycle.yml`.

2. **Enumerate objects** — `DescribeGlobal`,
   `GET /services/data/v{version}/sobjects/`.
   Returns every sObject the **calling user** can see, with per-object flags:
   `queryable`, `createable`, `updateable`, `deletable`, `custom`, `keyPrefix`. Filter on those
   flags rather than on a hardcoded list of object names — a non-`queryable` object will fail your
   SOQL no matter how well-formed it is.

3. **Describe one object in full** — `SObjectDescribe`,
   `GET /services/data/v{version}/sobjects/{SObject}/describe`.
   This is the big one: every field with `type`, `length`, `nillable`, `createable`, `updateable`,
   `externalId`, `unique`, picklist values, and every `childRelationships` and reference
   relationship. Build dynamic queries from this, never from memory.
   Use `SObjectBasicInformation` (`GET /sobjects/{SObject}/`) when you only need the object's
   metadata summary and recent items — it is much smaller.

4. **Check the org's headroom** — `getOrgLimits`,
   `GET /services/data/v{version}/limits`.
   Returns `{Max, Remaining}` for `DailyApiRequests`, `DailyBulkApiBatches`,
   `DailyStreamingApiEvents`, `ConcurrentAsyncGetReportInstances` and more. Call this before a
   large job so you fail fast instead of halfway through.

## Rules that will bite you

- **Describe is expensive and it counts against your quota.** Cache it. Key the cache on
  `(org, user, sObject, apiVersion)` — describe reflects the calling user's field-level security,
  so it is not safe to share a cached describe across users.
- **`keyPrefix` identifies the object from a record ID.** The first three characters of any
  Salesforce ID are the object's key prefix (`001` Account, `003` Contact, `006` Opportunity,
  `00Q` Lead, `500` Case). This is how you route an unknown ID. See
  `data-model/salesforce-data-model.yml`.
- **Record IDs come in 15- and 18-character forms.** The 15-character form is case-sensitive; the
  18-character form is case-insensitive and safe for systems that upper-case. Prefer 18.
- **`DescribeGlobal` output is large** — hundreds of objects in a mature org. Stream or filter it;
  do not naively load it into a prompt.
- **Errors are an array**: `[{"message", "errorCode", "fields"}]`.
  `NOT_FOUND` on a describe usually means the object exists but the user cannot see it, not that
  it is absent.
