# Salesforce (salesforce)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Salesforce is a cloud-based customer relationship management (CRM) platform that provides a comprehensive suite of enterprise applications for sales, service, marketing, and more.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI
- Analytics
- Cloud
- Commerce
- CRM
- Customer Service
- Enterprise
- Marketing
- Platform
- Sales

## Timestamps

- **Created:** 2025-06-05
- **Modified:** 2026-05-19

## APIs

### Salesforce REST API

The Salesforce REST API provides a simple and powerful web service interface to interact with Salesforce org data. It supports creating, reading, updating, deleting, and querying records using SOQL and SOSL, and is the primary API for building connected applications against Salesforce.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/)
- **Base URL:** `https://{instance}.salesforce.com/services/data`

#### Tags

- CRM
- Objects
- Records
- REST
- SOQL
- SOSL

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/quickstart.htm)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/dome_versions.htm)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_understanding_authentication.htm)
- [OpenAPI](openapi/salesforce-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/salesforce-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/salesforce-sobject-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/salesforce-query-result-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Salesforce SOAP API

The Salesforce SOAP API enables developers to use SOAP calls to create, retrieve, update, and delete records such as accounts, leads, and custom objects. It provides robust enterprise-grade integration capabilities and supports batch processing of records.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/](https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/)
- **Base URL:** `https://{instance}.salesforce.com/services/Soap`

#### Tags

- CRM
- Enterprise
- Objects
- Records
- SOAP

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_quickstart_intro.htm)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_calls_list.htm)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_concepts_security.htm)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Bulk API

The Salesforce Bulk API is a specialized REST-based interface that enables asynchronous processing of large numbers of records. It is optimized for loading or deleting large sets of data and supports CSV, XML, and JSON formats.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/](https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/)
- **Base URL:** `https://{instance}.salesforce.com/services/async`

#### Tags

- Bulk
- CRM
- Data Loading
- ETL
- Records

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/asynch_api_quickstart.htm)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/asynch_api_reference.htm)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/asynch_api_concepts_security.htm)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Bulk API 2.0

Salesforce Bulk API 2.0 is a simplified, REST-based interface for bulk data operations that improves on the original Bulk API. It uses a straightforward job model and supports CSV format for ingest and query jobs processing millions of records.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_bulk_v2.meta/api_bulk_v2/](https://developer.salesforce.com/docs/atlas.en-us.api_bulk_v2.meta/api_bulk_v2/)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v{version}/jobs`

#### Tags

- Bulk
- CRM
- Data Loading
- ETL
- Records

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_bulk_v2.meta/api_bulk_v2/)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.api_bulk_v2.meta/api_bulk_v2/get_job_info.htm)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_bulk_v2.meta/api_bulk_v2/bulk_api_2_0_security.htm)
- [OpenAPI](openapi/salesforce-bulk-api-2-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/salesforce-bulk-job-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Salesforce Streaming API

The Salesforce Streaming API uses a publish-subscribe model based on Bayeux/CometD to push near-real-time event notifications to subscribed clients. It supports PushTopic events for record changes and Generic Streaming events for custom notifications.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/](https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/)
- **Base URL:** `https://{instance}.salesforce.com/cometd`

#### Tags

- CRM
- Events
- Push Notifications
- Real-Time
- Streaming

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/intro_stream.htm)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/resources_top.htm)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/using_streaming_api_auth.htm)
- [AsyncAPI](asyncapi/salesforce-streaming-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Metadata API

The Salesforce Metadata API is a SOAP-based API that enables developers to retrieve, deploy, create, update, and delete customizations for Salesforce organizations. It is the foundation for tools like Salesforce CLI, Ant Migration Tool, and CI/CD pipelines.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/)
- **Base URL:** `https://{instance}.salesforce.com/services/Soap/m`

#### Tags

- Configuration
- CRM
- Deployment
- DevOps
- Metadata

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/meta_quickstart.htm)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/meta_types_list.htm)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/meta_auth.htm)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Tooling API

The Salesforce Tooling API provides SOAP and REST interfaces for building developer tools for Force.com applications. It exposes fine-grained access to Apex code, Visualforce pages, and other metadata for IDE integration, code coverage, and debugging workflows.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/](https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v{version}/tooling`

#### Tags

- Apex
- CRM
- Development
- IDE
- Tooling

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/tooling_api_objects_list.htm)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/intro_rest_resources.htm)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/intro_rest_overview.htm)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Connect API (Chatter)

The Salesforce Connect REST API (formerly Chatter API) provides access to Salesforce Chatter feeds, groups, users, topics, and file sharing features. It also exposes Experience Cloud (community) data and supports building custom social and collaboration experiences.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v{version}/chatter`

#### Tags

- Chatter
- Collaboration
- Connect
- CRM
- Feed
- Social

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/quickstart.htm)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_list.htm)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/authentication.htm)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Analytics REST API

The Salesforce Analytics REST API (also known as CRM Analytics or Wave API) provides programmatic access to CRM Analytics datasets, lenses, dashboards, and queries. Developers can read and write analytics assets and run SAQL queries against analytics datasets.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.bi_dev_guide_rest.meta/bi_dev_guide_rest/](https://developer.salesforce.com/docs/atlas.en-us.bi_dev_guide_rest.meta/bi_dev_guide_rest/)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v{version}/wave`

#### Tags

- Analytics
- CRM
- CRM Analytics
- Dashboards
- Reports
- Tableau CRM

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.bi_dev_guide_rest.meta/bi_dev_guide_rest/)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.bi_dev_guide_rest.meta/bi_dev_guide_rest/bi_rest_overview.htm)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.bi_dev_guide_rest.meta/bi_dev_guide_rest/bi_rest_resources_list.htm)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Reports and Dashboards REST API

The Salesforce Reports and Dashboards REST API enables developers to programmatically access report results, list reports and dashboards, and run and filter reports. It supports accessing standard and custom Salesforce reports without the need to navigate the UI.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_analytics.meta/api_analytics/](https://developer.salesforce.com/docs/atlas.en-us.api_analytics.meta/api_analytics/)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v{version}/analytics`

#### Tags

- Analytics
- CRM
- Dashboards
- Reports

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_analytics.meta/api_analytics/)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.api_analytics.meta/api_analytics/sforce_analytics_rest_api_getstarted.htm)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.api_analytics.meta/api_analytics/sforce_analytics_rest_api_resource_index.htm)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Einstein Platform Services API

The Salesforce Einstein Platform Services API provides REST-based access to Salesforce AI capabilities including image classification, object detection, and sentiment analysis. Developers can train custom models or use pre-built models for vision and natural language processing tasks.

- **Human URL:** [https://metamind.readme.io/](https://metamind.readme.io/)
- **Base URL:** `https://api.einstein.ai/v2`

#### Tags

- AI
- Computer Vision
- Einstein
- Machine Learning
- Natural Language Processing
- Prediction

#### Properties

- [Documentation](https://metamind.readme.io/)
- [Getting Started](https://metamind.readme.io/docs/getting-started)
- [API Reference](https://metamind.readme.io/reference)
- [Authentication](https://metamind.readme.io/docs/authentication)
- [Getting Started](https://trailhead.salesforce.com/en/content/learn/modules/einstein_platform_services)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Einstein Prediction Service API

The Salesforce Einstein Prediction Service API enables programmatic access to Einstein Analytics predictions and forecasts built on CRM data. It allows applications to retrieve AI-driven predictions for leads, opportunities, and custom objects configured in Salesforce.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.einstein_platform_services.meta/einstein_platform_services/](https://developer.salesforce.com/docs/atlas.en-us.einstein_platform_services.meta/einstein_platform_services/)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v{version}/einstein`

#### Tags

- AI
- CRM
- Einstein
- Machine Learning
- Prediction

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.einstein_platform_services.meta/einstein_platform_services/)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.einstein_platform_services.meta/einstein_platform_services/einstein_platform_intro.htm)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce GraphQL API

The Salesforce GraphQL API provides a GraphQL interface to query and mutate Salesforce data. It allows clients to request exactly the data they need in a single request, reducing over-fetching and under-fetching compared to traditional REST calls.

- **Human URL:** [https://developer.salesforce.com/docs/platform/graphql/guide/graphql-about.html](https://developer.salesforce.com/docs/platform/graphql/guide/graphql-about.html)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v{version}/graphql`

#### Tags

- CRM
- GraphQL
- Queries
- Records

#### Properties

- [Documentation](https://developer.salesforce.com/docs/platform/graphql/guide/graphql-about.html)
- [Getting Started](https://developer.salesforce.com/docs/platform/graphql/guide/graphql-get-started.html)
- [API Reference](https://developer.salesforce.com/docs/platform/graphql/guide/graphql-reference.html)
- [Authentication](https://developer.salesforce.com/docs/platform/graphql/guide/graphql-auth.html)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Pub/Sub API

The Salesforce Pub/Sub API is a gRPC-based API for publishing and subscribing to platform events, change data capture events, and other event types in real time. It supersedes the CometD-based Streaming API for high-throughput event-driven integrations.

- **Human URL:** [https://developer.salesforce.com/docs/platform/pub-sub-api/guide/pub-sub-api-intro.html](https://developer.salesforce.com/docs/platform/pub-sub-api/guide/pub-sub-api-intro.html)
- **Base URL:** `https://api.pubsub.salesforce.com`

#### Tags

- CRM
- Events
- gRPC
- Platform Events
- Pub/Sub
- Real-Time

#### Properties

- [Documentation](https://developer.salesforce.com/docs/platform/pub-sub-api/guide/pub-sub-api-intro.html)
- [Getting Started](https://developer.salesforce.com/docs/platform/pub-sub-api/guide/pub-sub-api-get-started.html)
- [API Reference](https://developer.salesforce.com/docs/platform/pub-sub-api/references/pubsub-api-reference.html)
- [Authentication](https://developer.salesforce.com/docs/platform/pub-sub-api/guide/pub-sub-api-auth.html)
- [GitHub Repository](https://github.com/developerforce/pub-sub-api)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Platform Events API

Salesforce Platform Events enables event-driven integration architectures built on the Salesforce platform. Developers define custom event types as Salesforce objects and publish or subscribe to events using the REST API, Apex, or Salesforce Flows.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/](https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v{version}/sobjects`

#### Tags

- CRM
- Event-Driven
- Events
- Integration
- Platform Events

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/platform_events_intro.htm)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/platform_events_subscribe_api.htm)
- [AsyncAPI](asyncapi/salesforce-platform-events-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Change Data Capture API

Salesforce Change Data Capture delivers change events that represent changes to Salesforce records including creates, updates, deletes, and undeletes. It enables external systems to receive near-real-time changes to Salesforce data for data replication and synchronization use cases.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.change_data_capture.meta/change_data_capture/](https://developer.salesforce.com/docs/atlas.en-us.change_data_capture.meta/change_data_capture/)
- **Base URL:** `https://{instance}.salesforce.com/cometd`

#### Tags

- CDC
- Change Data Capture
- CRM
- Events
- Integration

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.change_data_capture.meta/change_data_capture/)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.change_data_capture.meta/change_data_capture/cdc_intro.htm)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.change_data_capture.meta/change_data_capture/cdc_subscribe_api.htm)
- [AsyncAPI](asyncapi/salesforce-change-data-capture-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce UI API

The Salesforce UI API provides a comprehensive REST interface for building UIs that work with Salesforce metadata and data. It returns layout information, picklist values, list views, record data, and object metadata that Lightning components rely on.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/](https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v{version}/ui-api`

#### Tags

- Components
- CRM
- Lightning
- UI
- User Interface

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/ui_api_get_started.htm)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/ui_api_resources_list.htm)
- [OpenAPI](openapi/salesforce-ui-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Composite API

The Salesforce Composite API allows developers to combine multiple Salesforce REST API requests into a single HTTP call. It reduces the number of round trips to the server and supports dependent requests using reference IDs, improving integration performance.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_composite.htm](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_composite.htm)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v{version}/composite`

#### Tags

- Batch
- Composite
- CRM
- Performance
- REST

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_composite.htm)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_composite_intro.htm)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Apex REST API

Salesforce Apex REST enables developers to expose custom Apex classes as RESTful web services. By annotating Apex classes and methods with @RestResource and HTTP method annotations, developers can create custom API endpoints that extend Salesforce functionality.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_rest.htm](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_rest.htm)
- **Base URL:** `https://{instance}.salesforce.com/services/apexrest`

#### Tags

- Apex
- CRM
- Custom APIs
- Development
- REST

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_rest.htm)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_rest_code_sample_intro.htm)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_rest_methods.htm)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Data Cloud API

The Salesforce Data Cloud API provides programmatic access to Data Cloud (formerly Customer Data Platform) for ingesting, querying, and managing unified customer profiles. It enables applications to read and write segments, calculated insights, and identity-resolved profile data.

- **Human URL:** [https://developer.salesforce.com/docs/platform/data-cloud-api/overview](https://developer.salesforce.com/docs/platform/data-cloud-api/overview)
- **Base URL:** `https://{instance}.salesforce.com/api/v1`

#### Tags

- CDP
- CRM
- Customer Data Platform
- Data Cloud
- Identity Resolution

#### Properties

- [Documentation](https://developer.salesforce.com/docs/platform/data-cloud-api/overview)
- [Getting Started](https://developer.salesforce.com/docs/platform/data-cloud-api/guide/dc-api-getting-started.html)
- [API Reference](https://developer.salesforce.com/docs/platform/data-cloud-api/references/data-cloud-api.html)
- [Authentication](https://developer.salesforce.com/docs/platform/data-cloud-api/guide/dc-api-auth.html)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Marketing Cloud REST API

The Salesforce Marketing Cloud REST API provides access to Marketing Cloud resources including contacts, journeys, data extensions, triggered sends, and transactional messaging. It uses OAuth 2.0 for authentication and is the primary interface for programmatic Marketing Cloud integrations.

- **Human URL:** [https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/rest-api.html](https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/rest-api.html)
- **Base URL:** `https://{subdomain}.rest.marketingcloudapis.com`

#### Tags

- Email
- Journeys
- Marketing Automation
- Marketing Cloud
- REST

#### Properties

- [Documentation](https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/rest-api.html)
- [Getting Started](https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/get-started-spec.html)
- [API Reference](https://developer.salesforce.com/docs/marketing/marketing-cloud/references/mc_rest_overview.html)
- [Authentication](https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/access-token-s2s.html)
- [OpenAPI](openapi/salesforce-marketing-cloud-rest-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Marketing Cloud SOAP API

The Salesforce Marketing Cloud SOAP API is a full-featured SOAP web service interface for Marketing Cloud that supports subscriber management, email send operations, automation activities, and data extension management.

- **Human URL:** [https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/soap-api.html](https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/soap-api.html)
- **Base URL:** `https://{subdomain}.soap.marketingcloudapis.com`

#### Tags

- Email
- Marketing Automation
- Marketing Cloud
- SOAP

#### Properties

- [Documentation](https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/soap-api.html)
- [Getting Started](https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/getting-started-with-mc-sdk.html)
- [API Reference](https://developer.salesforce.com/docs/marketing/marketing-cloud/references/mc_soap_objects.html)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Pardot API (Account Engagement)

The Salesforce Pardot API (now called Account Engagement API) provides programmatic access to Pardot marketing automation data including prospects, campaigns, forms, lists, and email statistics for B2B marketing use cases.

- **Human URL:** [https://developer.salesforce.com/docs/marketing/pardot/guide/overview.html](https://developer.salesforce.com/docs/marketing/pardot/guide/overview.html)
- **Base URL:** `https://pi.pardot.com/api`

#### Tags

- Account Engagement
- B2B Marketing
- Lead Generation
- Marketing
- Pardot

#### Properties

- [Documentation](https://developer.salesforce.com/docs/marketing/pardot/guide/overview.html)
- [Getting Started](https://developer.salesforce.com/docs/marketing/pardot/guide/getting-started.html)
- [API Reference](https://developer.salesforce.com/docs/marketing/pardot/references/pardot-api-overview.html)
- [Authentication](https://developer.salesforce.com/docs/marketing/pardot/guide/authentication.html)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Commerce Cloud OCAPI

The Salesforce Commerce Cloud Open Commerce API (OCAPI) provides a REST interface for accessing Salesforce B2C Commerce data and functionality including products, catalogs, orders, promotions, and customer accounts for storefronts and back-office integrations.

- **Human URL:** [https://developer.salesforce.com/docs/commerce/b2c-commerce/guide/OCAPI.html](https://developer.salesforce.com/docs/commerce/b2c-commerce/guide/OCAPI.html)
- **Base URL:** `https://{instance}.dx.commercecloud.salesforce.com`

#### Tags

- B2C Commerce
- Commerce
- OCAPI
- Orders
- Storefront

#### Properties

- [Documentation](https://developer.salesforce.com/docs/commerce/b2c-commerce/guide/OCAPI.html)
- [Getting Started](https://developer.salesforce.com/docs/commerce/b2c-commerce/guide/ocapi-get-started.html)
- [API Reference](https://developer.salesforce.com/docs/commerce/b2c-commerce/references/b2c-commerce-api.html)
- [Authentication](https://developer.salesforce.com/docs/commerce/b2c-commerce/guide/auth-overview.html)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Commerce Cloud Shopper APIs (SCAPI)

The Salesforce Commerce Cloud Shopper APIs (SCAPI) are a modern set of REST APIs for building B2C Commerce storefronts and headless commerce experiences. They cover shopper authentication, products, search, baskets, orders, and customer account management.

- **Human URL:** [https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/web-api.html](https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/web-api.html)
- **Base URL:** `https://{shortCode}.api.commercecloud.salesforce.com`

#### Tags

- B2C Commerce
- Commerce
- Orders
- Products
- Shopper
- Storefront

#### Properties

- [Documentation](https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/web-api.html)
- [Getting Started](https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/build-your-first-commerce-app.html)
- [API Reference](https://developer.salesforce.com/docs/commerce/salesforce-commerce/references/shopper-products.html)
- [Authentication](https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/slas.html)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Field Service API

The Salesforce Field Service API provides access to Field Service Lightning data and operations including work orders, service appointments, resource scheduling, and mobile workforce management. It enables custom integrations with scheduling systems and field service tools.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.field_service_dev.meta/field_service_dev/](https://developer.salesforce.com/docs/atlas.en-us.field_service_dev.meta/field_service_dev/)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v{version}`

#### Tags

- Field Service
- Mobile
- Scheduling
- Service Cloud
- Work Orders

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.field_service_dev.meta/field_service_dev/)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.field_service_dev.meta/field_service_dev/fsl_developer_guide_intro.htm)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Health Cloud API

The Salesforce Health Cloud API provides FHIR R4-compliant REST APIs and platform APIs for accessing patient and provider data in Health Cloud. It enables healthcare applications to interact with clinical data, care plans, patient timelines, and care team information.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.health_cloud_object_reference.meta/health_cloud_object_reference/](https://developer.salesforce.com/docs/atlas.en-us.health_cloud_object_reference.meta/health_cloud_object_reference/)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v{version}`

#### Tags

- Clinical
- FHIR
- Health Cloud
- Healthcare
- Patients

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.health_cloud_object_reference.meta/health_cloud_object_reference/)
- [Getting Started](https://developer.salesforce.com/docs/health/health-cloud/guide/health-cloud-intro.html)
- [API Reference](https://developer.salesforce.com/docs/health/health-cloud/guide/fhir-api-overview.html)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Financial Services Cloud API

The Salesforce Financial Services Cloud API exposes financial services-specific data objects including financial accounts, assets, liabilities, financial goals, and household relationships. It enables wealth management, banking, and insurance applications to integrate with Salesforce CRM data.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.financial_services_cloud_object_reference.meta/financial_services_cloud_object_reference/](https://developer.salesforce.com/docs/atlas.en-us.financial_services_cloud_object_reference.meta/financial_services_cloud_object_reference/)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v{version}`

#### Tags

- Banking
- CRM
- Financial Services
- Insurance
- Wealth Management

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.financial_services_cloud_object_reference.meta/financial_services_cloud_object_reference/)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.financial_services_cloud_object_reference.meta/financial_services_cloud_object_reference/sforce_api_objects_interaction.htm)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Experience Cloud API

The Salesforce Experience Cloud API provides REST access to Experience Cloud (formerly Community Cloud) data including community membership, navigation, managed content, and knowledge articles. It enables developers to build custom portals and community-driven experiences.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.communities_dev.meta/communities_dev/](https://developer.salesforce.com/docs/atlas.en-us.communities_dev.meta/communities_dev/)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v{version}/connect/communities`

#### Tags

- Communities
- Experience Cloud
- Portals
- Sites

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.communities_dev.meta/communities_dev/)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.communities_dev.meta/communities_dev/communities_dev_intro.htm)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.communities_dev.meta/communities_dev/communities_dev_network.htm)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce MuleSoft Anypoint Platform API

The MuleSoft Anypoint Platform API provides programmatic access to the MuleSoft integration platform including API Manager, Runtime Manager, Exchange, and Access Management. It enables automation of API lifecycle management, deployment, and monitoring operations.

- **Human URL:** [https://anypoint.mulesoft.com/exchange/portals/anypoint-platform/](https://anypoint.mulesoft.com/exchange/portals/anypoint-platform/)
- **Base URL:** `https://anypoint.mulesoft.com/accounts/api`

#### Tags

- API Management
- Integration
- iPaaS
- MuleSoft

#### Properties

- [Documentation](https://anypoint.mulesoft.com/exchange/portals/anypoint-platform/)
- [Getting Started](https://docs.mulesoft.com/general/)
- [API Reference](https://anypoint.mulesoft.com/exchange/portals/anypoint-platform/)
- [Authentication](https://docs.mulesoft.com/access-management/)
- [GitHub Repository](https://github.com/mulesoft)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Tableau REST API

The Tableau REST API enables developers to programmatically manage Tableau Server and Tableau Cloud resources including workbooks, data sources, views, sites, users, and groups. It supports automation of Tableau administration and content lifecycle operations.

- **Human URL:** [https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api.htm](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api.htm)
- **Base URL:** `https://{server}/api/{version}`

#### Tags

- Analytics
- Business Intelligence
- Dashboards
- Data Visualization
- Tableau

#### Properties

- [Documentation](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api.htm)
- [Getting Started](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_get_started.htm)
- [API Reference](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_ref.htm)
- [Authentication](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_concepts_auth.htm)
- [SDK](https://help.tableau.com/current/api/tableau-api-guide/en-us/)
- [GitHub Repository](https://github.com/tableau)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Lightning Web Components (LWC)

Lightning Web Components (LWC) is Salesforce's standards-based JavaScript framework for building UI components on the Salesforce platform. It uses modern web standards including custom elements, templates, and decorators, and provides a reactive wire service for accessing Salesforce data via Lightning Data Service. LWC is the recommended component model for Lightning Experience, Experience Cloud, and Salesforce mobile, superseding the legacy Aura framework.

- **Human URL:** [https://developer.salesforce.com/docs/platform/lwc/overview](https://developer.salesforce.com/docs/platform/lwc/overview)
- **Base URL:** `https://developer.salesforce.com/docs/platform/lwc`

#### Tags

- Components
- JavaScript
- Lightning
- LWC
- UI Framework

#### Properties

- [Documentation](https://developer.salesforce.com/docs/platform/lwc/overview)
- [Getting Started](https://developer.salesforce.com/docs/platform/lwc/guide/get-started-lwc.html)
- [API Reference](https://developer.salesforce.com/docs/platform/lwc/guide/reference.html)
- [API Reference](https://developer.salesforce.com/docs/platform/lwc/guide/reference-ui-api.html)
- [GitHub Repository](https://github.com/salesforce/lwc)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Aura Components

Salesforce Aura Components is the legacy JavaScript component framework for building dynamic web applications on the Salesforce platform. It provides a data binding model, event system, and Apex controller integration through the Aura framework. Salesforce recommends migrating to Lightning Web Components for new development, but Aura components remain fully supported and can coexist with LWC components on the same page.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.lightning.meta/lightning/intro_framework.htm](https://developer.salesforce.com/docs/atlas.en-us.lightning.meta/lightning/intro_framework.htm)
- **Base URL:** `https://developer.salesforce.com/docs/atlas.en-us.lightning.meta/lightning`

#### Tags

- Aura
- Components
- JavaScript
- Legacy
- Lightning

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.lightning.meta/lightning/intro_framework.htm)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.lightning.meta/lightning/qs_aotp_app.htm)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.lightning.meta/lightning/ref_component_library.htm)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Lightning Design System (SLDS)

The Salesforce Lightning Design System (SLDS) provides HTML and CSS component blueprints, design tokens, and utility classes for building applications visually consistent with Salesforce Lightning Experience. Developers reference SLDS in Lightning Web Components, Aura components, and Visualforce pages to match Salesforce's design language without including SLDS directly, as it is automatically available in the Lightning runtime.

- **Human URL:** [https://www.lightningdesignsystem.com/](https://www.lightningdesignsystem.com/)
- **Base URL:** `https://www.lightningdesignsystem.com`

#### Tags

- Components
- CSS
- Design System
- Lightning
- UI

#### Properties

- [Documentation](https://www.lightningdesignsystem.com/)
- [Getting Started](https://developer.salesforce.com/docs/platform/lwc/guide/create-components-css-slds.html)
- [GitHub Repository](https://github.com/salesforce/design-system-react)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Agentforce Agent API

The Salesforce Agentforce Agent API is a REST API that enables developers to communicate with AI agents directly, starting sessions, sending messages, receiving responses, and ending sessions. It supports embedding agents on websites, creating headless agents for automation, and building multi-agent ecosystems.

- **Human URL:** [https://developer.salesforce.com/docs/ai/agentforce/guide/agent-api.html](https://developer.salesforce.com/docs/ai/agentforce/guide/agent-api.html)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v{version}/agent`

#### Tags

- Agentforce
- Agents
- AI
- Conversational AI
- GenAI
- REST

#### Properties

- [Documentation](https://developer.salesforce.com/docs/ai/agentforce/guide/agent-api.html)
- [Getting Started](https://developer.salesforce.com/docs/ai/agentforce/guide/agent-api-get-started.html)
- [API Reference](https://developer.salesforce.com/docs/ai/agentforce/references/agent-api)
- [Code Examples](https://developer.salesforce.com/docs/ai/agentforce/guide/agent-api-examples.html)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Models API

The Salesforce Models API provides Apex classes and REST endpoints that connect applications to large language models (LLMs) from Salesforce partners including Anthropic, Google, and OpenAI. It supports chat conversations, text generation, embeddings, and feedback collection, with all requests going through the Einstein Trust Layer.

- **Human URL:** [https://developer.salesforce.com/docs/ai/agentforce/guide/models-api.html](https://developer.salesforce.com/docs/ai/agentforce/guide/models-api.html)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v{version}/einstein`

#### Tags

- Agentforce
- AI
- Einstein
- GenAI
- LLM
- Machine Learning

#### Properties

- [Documentation](https://developer.salesforce.com/docs/ai/agentforce/guide/models-api.html)
- [Getting Started](https://developer.salesforce.com/docs/ai/agentforce/guide/models-get-started.html)
- [API Reference](https://developer.salesforce.com/docs/ai/agentforce/guide/access-models-api-with-rest.html)
- [Documentation](https://developer.salesforce.com/docs/ai/agentforce/guide/supported-models.html)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Interaction Service API

The Salesforce Interaction Service API enables automation and customization of the Bring Your Own Channel (BYOC) experience for messaging. It sends inbound messaging interactions from external end-user clients to Salesforce, including static content messages, typing indicators, file attachments, and message status updates.

- **Human URL:** [https://developer.salesforce.com/docs/service/interaction-service-api/overview](https://developer.salesforce.com/docs/service/interaction-service-api/overview)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v{version}`

#### Tags

- BYOC
- Customer Service
- Messaging
- Omnichannel
- Service Cloud

#### Properties

- [Documentation](https://developer.salesforce.com/docs/service/interaction-service-api/overview)
- [Getting Started](https://developer.salesforce.com/docs/service/interaction-service-api/guide/get-started.html)
- [API Reference](https://developer.salesforce.com/docs/service/interaction-service-api/references)
- [Authentication](https://developer.salesforce.com/docs/service/interaction-service-api/guide/authorization.html)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce B2B Commerce API

The Salesforce B2B Commerce API provides REST endpoints for handling commerce data in B2B and D2C storefronts. It offers support for address management, cart management, checkout processing, order management, product handling, pricing, promotions, tax management, wishlist management, and search settings.

- **Human URL:** [https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/b2b-d2c-comm-storefront-apis-parent.html](https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/b2b-d2c-comm-storefront-apis-parent.html)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v{version}/commerce`

#### Tags

- B2B Commerce
- Cart
- Commerce
- Orders
- Products
- Storefront

#### Properties

- [Documentation](https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/b2b-d2c-comm-storefront-apis-parent.html)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.b2b_b2c_comm_dev.meta/b2b_b2c_comm_dev/b2b_b2c_comm_dev_guide.htm)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_commerce.htm)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Actions API

The Salesforce Actions API provides a unified interface for invoking standard and custom actions across the Salesforce platform. It supports Apex actions, Flow actions, quick actions, and invocable actions, enabling developers to programmatically trigger automation and business logic from REST API calls.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_action.meta/api_action/actions_intro.htm](https://developer.salesforce.com/docs/atlas.en-us.api_action.meta/api_action/actions_intro.htm)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v{version}/actions`

#### Tags

- Actions
- Automation
- CRM
- Flow
- Invocable

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_action.meta/api_action/actions_intro.htm)
- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.api_action.meta/api_action/actions_intro_overview.htm)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_actions_invocable.htm)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce IoT REST API

The Salesforce IoT REST API provides programmatic access to Salesforce IoT data including contexts, orchestrations, and usage data. It enables developers to manage IoT events and orchestration rules for processing device data and triggering automated business actions.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_iot.meta/api_iot/](https://developer.salesforce.com/docs/atlas.en-us.api_iot.meta/api_iot/)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v{version}/iot`

#### Tags

- Events
- IoT
- Orchestrations
- REST

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_iot.meta/api_iot/)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_iot.meta/api_iot/qs_auth.htm)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.api_iot.meta/api_iot/examples_overview.htm)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Service Cloud Voice API

The Salesforce Service Cloud Voice API provides Telephony Integration REST API and Voice Toolkit API for programmatically managing voice calls and integrating telephony systems with Salesforce. It supports both Amazon Connect and partner telephony implementations for unified contact center experiences.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.voice_developer_guide.meta/voice_developer_guide/voice_intro.htm](https://developer.salesforce.com/docs/atlas.en-us.voice_developer_guide.meta/voice_developer_guide/voice_intro.htm)
- **Base URL:** `https://{instance}.salesforce.com/services/data/v{version}`

#### Tags

- Contact Center
- CTI
- Service Cloud
- Telephony
- Voice

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.voice_developer_guide.meta/voice_developer_guide/voice_intro.htm)
- [API Reference](https://developer.salesforce.com/docs/atlas.en-us.voice_developer_guide.meta/voice_developer_guide/voice_rest_overview.htm)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.voice_developer_guide.meta/voice_developer_guide/voice_rest_authorization.htm)
- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.voice_pt_developer_guide.meta/voice_pt_developer_guide/voice_pt_dev_guide.htm)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce Mobile SDK

The Salesforce Mobile SDK provides libraries and tools for building native and hybrid mobile applications on iOS and Android that integrate with the Salesforce platform. It supports Swift, Objective-C, Java, Kotlin, and React Native development with built-in authentication, data synchronization, and offline capabilities.

- **Human URL:** [https://developer.salesforce.com/docs/platform/mobile-sdk/overview](https://developer.salesforce.com/docs/platform/mobile-sdk/overview)
- **Base URL:** `https://developer.salesforce.com/docs/platform/mobile-sdk`

#### Tags

- Android
- iOS
- Mobile
- React Native
- SDK

#### Properties

- [Documentation](https://developer.salesforce.com/docs/platform/mobile-sdk/overview)
- [Getting Started](https://developer.salesforce.com/docs/platform/mobile-sdk/guide/intro.html)
- [Portal](https://developer.salesforce.com/developer-centers/mobile)
- [GitHub Repository](https://github.com/forcedotcom/SalesforceMobileSDK-Android)
- [Postman Collection](collections/salesforce-bulk-api-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-bulk-api-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-marketing-cloud-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-marketing-cloud-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce-ui-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-ui-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salesforce

Salesforce is a cloud-based customer relationship management (CRM) platform that helps organizations manage and grow customer relationships across the entire lifecycle. It unifies sales, service, marketing, and commerce so teams can track leads and opportunities, support customers, run campaigns, and transact in one place.

- **Human URL:** [https://developer.salesforce.com/](https://developer.salesforce.com/)

#### Tags

- CRM

#### Properties

- [Documentation](https://developer.salesforce.com/)
- [OpenAPI](openapi/salesforce-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salesforce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://developer.salesforce.com/)
- [Documentation](https://developer.salesforce.com/)
- [Getting Started](https://trailhead.salesforce.com/)
- [Status Page](https://status.salesforce.com/)
- [Support](https://help.salesforce.com/)
- [Community](https://trailblazers.salesforce.com/)
- [Authentication](https://help.salesforce.com/s/articleView?id=sf.remoteaccess_authenticate.htm)
- [O Auth  Documentation](https://help.salesforce.com/s/articleView?id=sf.remoteaccess_oauth_flows.htm)
- [A P I  Versions](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/dome_versions.htm)
- [Postman  Collection](https://www.postman.com/salesforce-developers/)
- [GitHub Organization](https://github.com/salesforce)
- [Terms of Service](https://www.salesforce.com/company/legal/agreements/)
- [Privacy Policy](https://www.salesforce.com/company/privacy/)
- [Sign Up](https://login.salesforce.com/)
- [Sign Up](https://developer.salesforce.com/signup)
- [Console](https://login.salesforce.com/)
- [Marketplace](https://appexchange.salesforce.com/)
- [Blog](https://developer.salesforce.com/blogs/)
- [SDK](https://developer.salesforce.com/tools/salesforcecli)
- [SDK](https://developer.salesforce.com/tools/)
- [Changelog](https://developer.salesforce.com/release-notes/)
- [Stack Overflow](https://salesforce.stackexchange.com/)
- [Pricing](https://www.salesforce.com/pricing/)
- [X (Twitter)](https://twitter.com/salesforcedevs)
- [LinkedIn](https://www.linkedin.com/showcase/salesforce-developers)
- [YouTube](https://www.youtube.com/@salesforcedevelopers)
- [Rate Limits](https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm)
- [Security](https://security.salesforce.com/security-advisories)
- [Security](https://developer.salesforce.com/developer-centers/security)
- [Security](https://developer.salesforce.com/docs/atlas.en-us.secure_coding_guide.meta/secure_coding_guide/secure_coding_guidelines.htm)
- [Release Notes](https://help.salesforce.com/s/articleView?id=release-notes.salesforce_release_notes.htm&language=en_US)
- [Events](https://www.salesforce.com/events/)
- [Events](https://www.salesforce.com/dreamforce/)
- [Portal](https://developer.salesforce.com/developer-centers/integration-apis)
- [A P I  Library](https://developer.salesforce.com/docs/apis)
- [Portal](https://developer.salesforce.com/developer-centers/mobile)
- [JSON-LD](json-ld/salesforce-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/salesforce-sobject-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/salesforce-query-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/salesforce-bulk-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/salesforce-rest-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/salesforce-bulk-2-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/salesforce-ui-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/salesforce-spectral-rules.yml)
- [Vocabulary](vocabulary/salesforce-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
