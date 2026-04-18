# Salesforce (salesforce)
Salesforce is a cloud-based customer relationship management (CRM) platform that provides a comprehensive suite of enterprise applications for sales, service, marketing, and more.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/salesforce/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AI, Analytics, Cloud, Commerce, CRM, Customer Service, Enterprise, Marketing, Platform, Sales

## Timestamps

- **Created:** 2025-06-05
- **Modified:** 2026-04-18

## APIs

### Salesforce REST API
The Salesforce REST API provides a simple and powerful web service interface to interact with Salesforce org data. It supports creating, reading, updating, deleting, and querying records using SOQL and SOSL, and is the primary API for building connected applications against Salesforce.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/)

#### Tags:

 - CRM, Objects, Records, REST, SOQL, SOSL

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/)
- [GettingStarted](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/quickstart.htm)
- [APIReference](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/dome_versions.htm)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_understanding_authentication.htm)
- [OpenAPI](openapi/salesforce-openapi.yml)
- [OpenAPI](openapi/salesforce-rest-api-openapi.yml)
- [JSONSchema](json-schema/salesforce-sobject-schema.json)
- [JSONSchema](json-schema/salesforce-query-result-schema.json)

### Salesforce SOAP API
The Salesforce SOAP API enables developers to use SOAP calls to create, retrieve, update, and delete records such as accounts, leads, and custom objects. It provides robust enterprise-grade integration capabilities and supports batch processing of records.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/](https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/)

#### Tags:

 - CRM, Enterprise, Objects, Records, SOAP

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/)
- [GettingStarted](https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_quickstart_intro.htm)
- [APIReference](https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_calls_list.htm)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_concepts_security.htm)

### Salesforce Bulk API
The Salesforce Bulk API is a specialized REST-based interface that enables asynchronous processing of large numbers of records. It is optimized for loading or deleting large sets of data and supports CSV, XML, and JSON formats.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/](https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/)

#### Tags:

 - Bulk, CRM, Data Loading, ETL, Records

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/)
- [GettingStarted](https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/asynch_api_quickstart.htm)
- [APIReference](https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/asynch_api_reference.htm)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch/asynch_api_concepts_security.htm)

### Salesforce Bulk API 2.0
Salesforce Bulk API 2.0 is a simplified, REST-based interface for bulk data operations that improves on the original Bulk API. It uses a straightforward job model and supports CSV format for ingest and query jobs processing millions of records.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_bulk_v2.meta/api_bulk_v2/](https://developer.salesforce.com/docs/atlas.en-us.api_bulk_v2.meta/api_bulk_v2/)

#### Tags:

 - Bulk, CRM, Data Loading, ETL, Records

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_bulk_v2.meta/api_bulk_v2/)
- [APIReference](https://developer.salesforce.com/docs/atlas.en-us.api_bulk_v2.meta/api_bulk_v2/get_job_info.htm)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_bulk_v2.meta/api_bulk_v2/bulk_api_2_0_security.htm)
- [OpenAPI](openapi/salesforce-bulk-api-2-openapi.yml)
- [JSONSchema](json-schema/salesforce-bulk-job-schema.json)

### Salesforce Streaming API
The Salesforce Streaming API uses a publish-subscribe model based on Bayeux/CometD to push near-real-time event notifications to subscribed clients. It supports PushTopic events for record changes and Generic Streaming events for custom notifications.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/](https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/)

#### Tags:

 - CRM, Events, Push Notifications, Real-Time, Streaming

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/)
- [GettingStarted](https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/intro_stream.htm)
- [APIReference](https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/resources_top.htm)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming/using_streaming_api_auth.htm)
- [AsyncAPI](asyncapi/salesforce-streaming-asyncapi.yml)

### Salesforce Metadata API
The Salesforce Metadata API is a SOAP-based API that enables developers to retrieve, deploy, create, update, and delete customizations for Salesforce organizations. It is the foundation for tools like Salesforce CLI, Ant Migration Tool, and CI/CD pipelines.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/)

#### Tags:

 - Configuration, CRM, Deployment, DevOps, Metadata

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/)
- [GettingStarted](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/meta_quickstart.htm)
- [APIReference](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/meta_types_list.htm)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta/meta_auth.htm)

### Salesforce Tooling API
The Salesforce Tooling API provides SOAP and REST interfaces for building developer tools for Force.com applications. It exposes fine-grained access to Apex code, Visualforce pages, and other metadata for IDE integration, code coverage, and debugging workflows.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/](https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/)

#### Tags:

 - Apex, CRM, Development, IDE, Tooling

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/)
- [APIReference](https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/tooling_api_objects_list.htm)
- [GettingStarted](https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/intro_rest_resources.htm)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_tooling.meta/api_tooling/intro_rest_overview.htm)

### Salesforce Connect API (Chatter)
The Salesforce Connect REST API (formerly Chatter API) provides access to Salesforce Chatter feeds, groups, users, topics, and file sharing features. It also exposes Experience Cloud (community) data and supports building custom social and collaboration experiences.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/)

#### Tags:

 - Chatter, Collaboration, Connect, CRM, Feed, Social

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/)
- [GettingStarted](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/quickstart.htm)
- [APIReference](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_list.htm)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/authentication.htm)

### Salesforce Analytics REST API
The Salesforce Analytics REST API (also known as CRM Analytics or Wave API) provides programmatic access to CRM Analytics datasets, lenses, dashboards, and queries. Developers can read and write analytics assets and run SAQL queries against analytics datasets.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.bi_dev_guide_rest.meta/bi_dev_guide_rest/](https://developer.salesforce.com/docs/atlas.en-us.bi_dev_guide_rest.meta/bi_dev_guide_rest/)

#### Tags:

 - Analytics, CRM, CRM Analytics, Dashboards, Reports, Tableau CRM

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.bi_dev_guide_rest.meta/bi_dev_guide_rest/)
- [GettingStarted](https://developer.salesforce.com/docs/atlas.en-us.bi_dev_guide_rest.meta/bi_dev_guide_rest/bi_rest_overview.htm)
- [APIReference](https://developer.salesforce.com/docs/atlas.en-us.bi_dev_guide_rest.meta/bi_dev_guide_rest/bi_rest_resources_list.htm)

### Salesforce Reports and Dashboards REST API
The Salesforce Reports and Dashboards REST API enables developers to programmatically access report results, list reports and dashboards, and run and filter reports. It supports accessing standard and custom Salesforce reports without the need to navigate the UI.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_analytics.meta/api_analytics/](https://developer.salesforce.com/docs/atlas.en-us.api_analytics.meta/api_analytics/)

#### Tags:

 - Analytics, CRM, Dashboards, Reports

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_analytics.meta/api_analytics/)
- [GettingStarted](https://developer.salesforce.com/docs/atlas.en-us.api_analytics.meta/api_analytics/sforce_analytics_rest_api_getstarted.htm)
- [APIReference](https://developer.salesforce.com/docs/atlas.en-us.api_analytics.meta/api_analytics/sforce_analytics_rest_api_resource_index.htm)

### Salesforce Einstein Platform Services API
The Salesforce Einstein Platform Services API provides REST-based access to Salesforce AI capabilities including image classification, object detection, and sentiment analysis. Developers can train custom models or use pre-built models for vision and natural language processing tasks.

**Human URL:** [https://metamind.readme.io/](https://metamind.readme.io/)

#### Tags:

 - AI, Computer Vision, Einstein, Machine Learning, Natural Language Processing, Prediction

#### Properties

- [Documentation](https://metamind.readme.io/)
- [GettingStarted](https://metamind.readme.io/docs/getting-started)
- [APIReference](https://metamind.readme.io/reference)
- [Authentication](https://metamind.readme.io/docs/authentication)
- [GettingStarted](https://trailhead.salesforce.com/en/content/learn/modules/einstein_platform_services)

### Salesforce Einstein Prediction Service API
The Salesforce Einstein Prediction Service API enables programmatic access to Einstein Analytics predictions and forecasts built on CRM data. It allows applications to retrieve AI-driven predictions for leads, opportunities, and custom objects configured in Salesforce.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.einstein_platform_services.meta/einstein_platform_services/](https://developer.salesforce.com/docs/atlas.en-us.einstein_platform_services.meta/einstein_platform_services/)

#### Tags:

 - AI, CRM, Einstein, Machine Learning, Prediction

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.einstein_platform_services.meta/einstein_platform_services/)
- [GettingStarted](https://developer.salesforce.com/docs/atlas.en-us.einstein_platform_services.meta/einstein_platform_services/einstein_platform_intro.htm)

### Salesforce GraphQL API
The Salesforce GraphQL API provides a GraphQL interface to query and mutate Salesforce data. It allows clients to request exactly the data they need in a single request, reducing over-fetching and under-fetching compared to traditional REST calls.

**Human URL:** [https://developer.salesforce.com/docs/platform/graphql/guide/graphql-about.html](https://developer.salesforce.com/docs/platform/graphql/guide/graphql-about.html)

#### Tags:

 - CRM, GraphQL, Queries, Records

#### Properties

- [Documentation](https://developer.salesforce.com/docs/platform/graphql/guide/graphql-about.html)
- [GettingStarted](https://developer.salesforce.com/docs/platform/graphql/guide/graphql-get-started.html)
- [APIReference](https://developer.salesforce.com/docs/platform/graphql/guide/graphql-reference.html)
- [Authentication](https://developer.salesforce.com/docs/platform/graphql/guide/graphql-auth.html)

### Salesforce Pub/Sub API
The Salesforce Pub/Sub API is a gRPC-based API for publishing and subscribing to platform events, change data capture events, and other event types in real time. It supersedes the CometD-based Streaming API for high-throughput event-driven integrations.

**Human URL:** [https://developer.salesforce.com/docs/platform/pub-sub-api/guide/pub-sub-api-intro.html](https://developer.salesforce.com/docs/platform/pub-sub-api/guide/pub-sub-api-intro.html)

#### Tags:

 - CRM, Events, gRPC, Platform Events, Pub/Sub, Real-Time

#### Properties

- [Documentation](https://developer.salesforce.com/docs/platform/pub-sub-api/guide/pub-sub-api-intro.html)
- [GettingStarted](https://developer.salesforce.com/docs/platform/pub-sub-api/guide/pub-sub-api-get-started.html)
- [APIReference](https://developer.salesforce.com/docs/platform/pub-sub-api/references/pubsub-api-reference.html)
- [Authentication](https://developer.salesforce.com/docs/platform/pub-sub-api/guide/pub-sub-api-auth.html)
- [GitHubRepository](https://github.com/developerforce/pub-sub-api)

### Salesforce Platform Events API
Salesforce Platform Events enables event-driven integration architectures built on the Salesforce platform. Developers define custom event types as Salesforce objects and publish or subscribe to events using the REST API, Apex, or Salesforce Flows.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/](https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/)

#### Tags:

 - CRM, Event-Driven, Events, Integration, Platform Events

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/)
- [GettingStarted](https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/platform_events_intro.htm)
- [APIReference](https://developer.salesforce.com/docs/atlas.en-us.platform_events.meta/platform_events/platform_events_subscribe_api.htm)
- [AsyncAPI](asyncapi/salesforce-platform-events-asyncapi.yml)

### Salesforce Change Data Capture API
Salesforce Change Data Capture delivers change events that represent changes to Salesforce records including creates, updates, deletes, and undeletes. It enables external systems to receive near-real-time changes to Salesforce data for data replication and synchronization use cases.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.change_data_capture.meta/change_data_capture/](https://developer.salesforce.com/docs/atlas.en-us.change_data_capture.meta/change_data_capture/)

#### Tags:

 - CDC, Change Data Capture, CRM, Events, Integration

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.change_data_capture.meta/change_data_capture/)
- [GettingStarted](https://developer.salesforce.com/docs/atlas.en-us.change_data_capture.meta/change_data_capture/cdc_intro.htm)
- [APIReference](https://developer.salesforce.com/docs/atlas.en-us.change_data_capture.meta/change_data_capture/cdc_subscribe_api.htm)
- [AsyncAPI](asyncapi/salesforce-change-data-capture-asyncapi.yml)

### Salesforce UI API
The Salesforce UI API provides a comprehensive REST interface for building UIs that work with Salesforce metadata and data. It returns layout information, picklist values, list views, record data, and object metadata that Lightning components rely on.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/](https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/)

#### Tags:

 - Components, CRM, Lightning, UI, User Interface

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/)
- [GettingStarted](https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/ui_api_get_started.htm)
- [APIReference](https://developer.salesforce.com/docs/atlas.en-us.uiapi.meta/uiapi/ui_api_resources_list.htm)
- [OpenAPI](openapi/salesforce-ui-api-openapi.yml)

### Salesforce Composite API
The Salesforce Composite API allows developers to combine multiple Salesforce REST API requests into a single HTTP call. It reduces the number of round trips to the server and supports dependent requests using reference IDs, improving integration performance.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_composite.htm](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_composite.htm)

#### Tags:

 - Batch, Composite, CRM, Performance, REST

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_composite.htm)
- [APIReference](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_composite_intro.htm)

### Salesforce Apex REST API
Salesforce Apex REST enables developers to expose custom Apex classes as RESTful web services. By annotating Apex classes and methods with @RestResource and HTTP method annotations, developers can create custom API endpoints that extend Salesforce functionality.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_rest.htm](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_rest.htm)

#### Tags:

 - Apex, CRM, Custom APIs, Development, REST

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_rest.htm)
- [GettingStarted](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_rest_code_sample_intro.htm)
- [APIReference](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_rest_methods.htm)

### Salesforce Data Cloud API
The Salesforce Data Cloud API provides programmatic access to Data Cloud (formerly Customer Data Platform) for ingesting, querying, and managing unified customer profiles. It enables applications to read and write segments, calculated insights, and identity-resolved profile data.

**Human URL:** [https://developer.salesforce.com/docs/platform/data-cloud-api/overview](https://developer.salesforce.com/docs/platform/data-cloud-api/overview)

#### Tags:

 - CDP, CRM, Customer Data Platform, Data Cloud, Identity Resolution

#### Properties

- [Documentation](https://developer.salesforce.com/docs/platform/data-cloud-api/overview)
- [GettingStarted](https://developer.salesforce.com/docs/platform/data-cloud-api/guide/dc-api-getting-started.html)
- [APIReference](https://developer.salesforce.com/docs/platform/data-cloud-api/references/data-cloud-api.html)
- [Authentication](https://developer.salesforce.com/docs/platform/data-cloud-api/guide/dc-api-auth.html)

### Salesforce Marketing Cloud REST API
The Salesforce Marketing Cloud REST API provides access to Marketing Cloud resources including contacts, journeys, data extensions, triggered sends, and transactional messaging. It uses OAuth 2.0 for authentication and is the primary interface for programmatic Marketing Cloud integrations.

**Human URL:** [https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/rest-api.html](https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/rest-api.html)

#### Tags:

 - Email, Journeys, Marketing Automation, Marketing Cloud, REST

#### Properties

- [Documentation](https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/rest-api.html)
- [GettingStarted](https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/get-started-spec.html)
- [APIReference](https://developer.salesforce.com/docs/marketing/marketing-cloud/references/mc_rest_overview.html)
- [Authentication](https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/access-token-s2s.html)
- [OpenAPI](openapi/salesforce-marketing-cloud-rest-openapi.yml)

### Salesforce Marketing Cloud SOAP API
The Salesforce Marketing Cloud SOAP API is a full-featured SOAP web service interface for Marketing Cloud that supports subscriber management, email send operations, automation activities, and data extension management.

**Human URL:** [https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/soap-api.html](https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/soap-api.html)

#### Tags:

 - Email, Marketing Automation, Marketing Cloud, SOAP

#### Properties

- [Documentation](https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/soap-api.html)
- [GettingStarted](https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/getting-started-with-mc-sdk.html)
- [APIReference](https://developer.salesforce.com/docs/marketing/marketing-cloud/references/mc_soap_objects.html)

### Salesforce Pardot API (Account Engagement)
The Salesforce Pardot API (now called Account Engagement API) provides programmatic access to Pardot marketing automation data including prospects, campaigns, forms, lists, and email statistics for B2B marketing use cases.

**Human URL:** [https://developer.salesforce.com/docs/marketing/pardot/guide/overview.html](https://developer.salesforce.com/docs/marketing/pardot/guide/overview.html)

#### Tags:

 - Account Engagement, B2B Marketing, Lead Generation, Marketing, Pardot

#### Properties

- [Documentation](https://developer.salesforce.com/docs/marketing/pardot/guide/overview.html)
- [GettingStarted](https://developer.salesforce.com/docs/marketing/pardot/guide/getting-started.html)
- [APIReference](https://developer.salesforce.com/docs/marketing/pardot/references/pardot-api-overview.html)
- [Authentication](https://developer.salesforce.com/docs/marketing/pardot/guide/authentication.html)

### Salesforce Commerce Cloud OCAPI
The Salesforce Commerce Cloud Open Commerce API (OCAPI) provides a REST interface for accessing Salesforce B2C Commerce data and functionality including products, catalogs, orders, promotions, and customer accounts for storefronts and back-office integrations.

**Human URL:** [https://developer.salesforce.com/docs/commerce/b2c-commerce/guide/OCAPI.html](https://developer.salesforce.com/docs/commerce/b2c-commerce/guide/OCAPI.html)

#### Tags:

 - B2C Commerce, Commerce, OCAPI, Orders, Storefront

#### Properties

- [Documentation](https://developer.salesforce.com/docs/commerce/b2c-commerce/guide/OCAPI.html)
- [GettingStarted](https://developer.salesforce.com/docs/commerce/b2c-commerce/guide/ocapi-get-started.html)
- [APIReference](https://developer.salesforce.com/docs/commerce/b2c-commerce/references/b2c-commerce-api.html)
- [Authentication](https://developer.salesforce.com/docs/commerce/b2c-commerce/guide/auth-overview.html)

### Salesforce Commerce Cloud Shopper APIs (SCAPI)
The Salesforce Commerce Cloud Shopper APIs (SCAPI) are a modern set of REST APIs for building B2C Commerce storefronts and headless commerce experiences. They cover shopper authentication, products, search, baskets, orders, and customer account management.

**Human URL:** [https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/web-api.html](https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/web-api.html)

#### Tags:

 - B2C Commerce, Commerce, Orders, Products, Shopper, Storefront

#### Properties

- [Documentation](https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/web-api.html)
- [GettingStarted](https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/build-your-first-commerce-app.html)
- [APIReference](https://developer.salesforce.com/docs/commerce/salesforce-commerce/references/shopper-products.html)
- [Authentication](https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/slas.html)

### Salesforce Field Service API
The Salesforce Field Service API provides access to Field Service Lightning data and operations including work orders, service appointments, resource scheduling, and mobile workforce management. It enables custom integrations with scheduling systems and field service tools.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.field_service_dev.meta/field_service_dev/](https://developer.salesforce.com/docs/atlas.en-us.field_service_dev.meta/field_service_dev/)

#### Tags:

 - Field Service, Mobile, Scheduling, Service Cloud, Work Orders

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.field_service_dev.meta/field_service_dev/)
- [GettingStarted](https://developer.salesforce.com/docs/atlas.en-us.field_service_dev.meta/field_service_dev/fsl_developer_guide_intro.htm)

### Salesforce Health Cloud API
The Salesforce Health Cloud API provides FHIR R4-compliant REST APIs and platform APIs for accessing patient and provider data in Health Cloud. It enables healthcare applications to interact with clinical data, care plans, patient timelines, and care team information.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.health_cloud_object_reference.meta/health_cloud_object_reference/](https://developer.salesforce.com/docs/atlas.en-us.health_cloud_object_reference.meta/health_cloud_object_reference/)

#### Tags:

 - Clinical, FHIR, Health Cloud, Healthcare, Patients

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.health_cloud_object_reference.meta/health_cloud_object_reference/)
- [GettingStarted](https://developer.salesforce.com/docs/health/health-cloud/guide/health-cloud-intro.html)
- [APIReference](https://developer.salesforce.com/docs/health/health-cloud/guide/fhir-api-overview.html)

### Salesforce Financial Services Cloud API
The Salesforce Financial Services Cloud API exposes financial services-specific data objects including financial accounts, assets, liabilities, financial goals, and household relationships. It enables wealth management, banking, and insurance applications to integrate with Salesforce CRM data.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.financial_services_cloud_object_reference.meta/financial_services_cloud_object_reference/](https://developer.salesforce.com/docs/atlas.en-us.financial_services_cloud_object_reference.meta/financial_services_cloud_object_reference/)

#### Tags:

 - Banking, CRM, Financial Services, Insurance, Wealth Management

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.financial_services_cloud_object_reference.meta/financial_services_cloud_object_reference/)
- [APIReference](https://developer.salesforce.com/docs/atlas.en-us.financial_services_cloud_object_reference.meta/financial_services_cloud_object_reference/sforce_api_objects_interaction.htm)

### Salesforce Experience Cloud API
The Salesforce Experience Cloud API provides REST access to Experience Cloud (formerly Community Cloud) data including community membership, navigation, managed content, and knowledge articles. It enables developers to build custom portals and community-driven experiences.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.communities_dev.meta/communities_dev/](https://developer.salesforce.com/docs/atlas.en-us.communities_dev.meta/communities_dev/)

#### Tags:

 - Communities, Experience Cloud, Portals, Sites

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.communities_dev.meta/communities_dev/)
- [GettingStarted](https://developer.salesforce.com/docs/atlas.en-us.communities_dev.meta/communities_dev/communities_dev_intro.htm)
- [APIReference](https://developer.salesforce.com/docs/atlas.en-us.communities_dev.meta/communities_dev/communities_dev_network.htm)

### Salesforce MuleSoft Anypoint Platform API
The MuleSoft Anypoint Platform API provides programmatic access to the MuleSoft integration platform including API Manager, Runtime Manager, Exchange, and Access Management. It enables automation of API lifecycle management, deployment, and monitoring operations.

**Human URL:** [https://anypoint.mulesoft.com/exchange/portals/anypoint-platform/](https://anypoint.mulesoft.com/exchange/portals/anypoint-platform/)

#### Tags:

 - API Management, Integration, iPaaS, MuleSoft

#### Properties

- [Documentation](https://anypoint.mulesoft.com/exchange/portals/anypoint-platform/)
- [GettingStarted](https://docs.mulesoft.com/general/)
- [APIReference](https://anypoint.mulesoft.com/exchange/portals/anypoint-platform/)
- [Authentication](https://docs.mulesoft.com/access-management/)
- [GitHubRepository](https://github.com/mulesoft)

### Salesforce Tableau REST API
The Tableau REST API enables developers to programmatically manage Tableau Server and Tableau Cloud resources including workbooks, data sources, views, sites, users, and groups. It supports automation of Tableau administration and content lifecycle operations.

**Human URL:** [https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api.htm](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api.htm)

#### Tags:

 - Analytics, Business Intelligence, Dashboards, Data Visualization, Tableau

#### Properties

- [Documentation](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api.htm)
- [GettingStarted](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_get_started.htm)
- [APIReference](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_ref.htm)
- [Authentication](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_concepts_auth.htm)
- [SDK](https://help.tableau.com/current/api/tableau-api-guide/en-us/)
- [GitHubRepository](https://github.com/tableau)

### Salesforce Lightning Web Components (LWC)
Lightning Web Components (LWC) is Salesforce's standards-based JavaScript framework for building UI components on the Salesforce platform.

**Human URL:** [https://developer.salesforce.com/docs/platform/lwc/overview](https://developer.salesforce.com/docs/platform/lwc/overview)

#### Tags:

 - Components, JavaScript, Lightning, LWC, UI Framework

#### Properties

- [Documentation](https://developer.salesforce.com/docs/platform/lwc/overview)
- [GettingStarted](https://developer.salesforce.com/docs/platform/lwc/guide/get-started-lwc.html)
- [APIReference](https://developer.salesforce.com/docs/platform/lwc/guide/reference.html)
- [APIReference](https://developer.salesforce.com/docs/platform/lwc/guide/reference-ui-api.html)
- [GitHubRepository](https://github.com/salesforce/lwc)

### Salesforce Aura Components
Salesforce Aura Components is the legacy JavaScript component framework for building dynamic web applications on the Salesforce platform.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.lightning.meta/lightning/intro_framework.htm](https://developer.salesforce.com/docs/atlas.en-us.lightning.meta/lightning/intro_framework.htm)

#### Tags:

 - Aura, Components, JavaScript, Legacy, Lightning

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.lightning.meta/lightning/intro_framework.htm)
- [GettingStarted](https://developer.salesforce.com/docs/atlas.en-us.lightning.meta/lightning/qs_aotp_app.htm)
- [APIReference](https://developer.salesforce.com/docs/atlas.en-us.lightning.meta/lightning/ref_component_library.htm)

### Salesforce Lightning Design System (SLDS)
The Salesforce Lightning Design System (SLDS) provides HTML and CSS component blueprints, design tokens, and utility classes for building applications visually consistent with Salesforce Lightning Experience.

**Human URL:** [https://www.lightningdesignsystem.com/](https://www.lightningdesignsystem.com/)

#### Tags:

 - Components, CSS, Design System, Lightning, UI

#### Properties

- [Documentation](https://www.lightningdesignsystem.com/)
- [GettingStarted](https://developer.salesforce.com/docs/platform/lwc/guide/create-components-css-slds.html)
- [GitHubRepository](https://github.com/salesforce/design-system-react)

### Salesforce Agentforce Agent API
The Salesforce Agentforce Agent API is a REST API that enables developers to communicate with AI agents directly, starting sessions, sending messages, receiving responses, and ending sessions.

**Human URL:** [https://developer.salesforce.com/docs/ai/agentforce/guide/agent-api.html](https://developer.salesforce.com/docs/ai/agentforce/guide/agent-api.html)

#### Tags:

 - Agentforce, Agents, AI, Conversational AI, GenAI, REST

#### Properties

- [Documentation](https://developer.salesforce.com/docs/ai/agentforce/guide/agent-api.html)
- [GettingStarted](https://developer.salesforce.com/docs/ai/agentforce/guide/agent-api-get-started.html)
- [APIReference](https://developer.salesforce.com/docs/ai/agentforce/references/agent-api)
- [CodeExamples](https://developer.salesforce.com/docs/ai/agentforce/guide/agent-api-examples.html)

### Salesforce Models API
The Salesforce Models API provides Apex classes and REST endpoints that connect applications to large language models (LLMs) from Salesforce partners including Anthropic, Google, and OpenAI.

**Human URL:** [https://developer.salesforce.com/docs/ai/agentforce/guide/models-api.html](https://developer.salesforce.com/docs/ai/agentforce/guide/models-api.html)

#### Tags:

 - Agentforce, AI, Einstein, GenAI, LLM, Machine Learning

#### Properties

- [Documentation](https://developer.salesforce.com/docs/ai/agentforce/guide/models-api.html)
- [GettingStarted](https://developer.salesforce.com/docs/ai/agentforce/guide/models-get-started.html)
- [APIReference](https://developer.salesforce.com/docs/ai/agentforce/guide/access-models-api-with-rest.html)
- [Documentation](https://developer.salesforce.com/docs/ai/agentforce/guide/supported-models.html)

### Salesforce Interaction Service API
The Salesforce Interaction Service API enables automation and customization of the Bring Your Own Channel (BYOC) experience for messaging.

**Human URL:** [https://developer.salesforce.com/docs/service/interaction-service-api/overview](https://developer.salesforce.com/docs/service/interaction-service-api/overview)

#### Tags:

 - BYOC, Customer Service, Messaging, Omnichannel, Service Cloud

#### Properties

- [Documentation](https://developer.salesforce.com/docs/service/interaction-service-api/overview)
- [GettingStarted](https://developer.salesforce.com/docs/service/interaction-service-api/guide/get-started.html)
- [APIReference](https://developer.salesforce.com/docs/service/interaction-service-api/references)
- [Authentication](https://developer.salesforce.com/docs/service/interaction-service-api/guide/authorization.html)

### Salesforce B2B Commerce API
The Salesforce B2B Commerce API provides REST endpoints for handling commerce data in B2B and D2C storefronts.

**Human URL:** [https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/b2b-d2c-comm-storefront-apis-parent.html](https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/b2b-d2c-comm-storefront-apis-parent.html)

#### Tags:

 - B2B Commerce, Cart, Commerce, Orders, Products, Storefront

#### Properties

- [Documentation](https://developer.salesforce.com/docs/commerce/salesforce-commerce/guide/b2b-d2c-comm-storefront-apis-parent.html)
- [GettingStarted](https://developer.salesforce.com/docs/atlas.en-us.b2b_b2c_comm_dev.meta/b2b_b2c_comm_dev/b2b_b2c_comm_dev_guide.htm)
- [APIReference](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi/connect_resources_commerce.htm)

### Salesforce Actions API
The Salesforce Actions API provides a unified interface for invoking standard and custom actions across the Salesforce platform.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_action.meta/api_action/actions_intro.htm](https://developer.salesforce.com/docs/atlas.en-us.api_action.meta/api_action/actions_intro.htm)

#### Tags:

 - Actions, Automation, CRM, Flow, Invocable

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_action.meta/api_action/actions_intro.htm)
- [GettingStarted](https://developer.salesforce.com/docs/atlas.en-us.api_action.meta/api_action/actions_intro_overview.htm)
- [APIReference](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_actions_invocable.htm)

### Salesforce IoT REST API
The Salesforce IoT REST API provides programmatic access to Salesforce IoT data including contexts, orchestrations, and usage data.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.api_iot.meta/api_iot/](https://developer.salesforce.com/docs/atlas.en-us.api_iot.meta/api_iot/)

#### Tags:

 - Events, IoT, Orchestrations, REST

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api_iot.meta/api_iot/)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_iot.meta/api_iot/qs_auth.htm)
- [APIReference](https://developer.salesforce.com/docs/atlas.en-us.api_iot.meta/api_iot/examples_overview.htm)

### Salesforce Service Cloud Voice API
The Salesforce Service Cloud Voice API provides Telephony Integration REST API and Voice Toolkit API for programmatically managing voice calls and integrating telephony systems with Salesforce.

**Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.voice_developer_guide.meta/voice_developer_guide/voice_intro.htm](https://developer.salesforce.com/docs/atlas.en-us.voice_developer_guide.meta/voice_developer_guide/voice_intro.htm)

#### Tags:

 - Contact Center, CTI, Service Cloud, Telephony, Voice

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.voice_developer_guide.meta/voice_developer_guide/voice_intro.htm)
- [APIReference](https://developer.salesforce.com/docs/atlas.en-us.voice_developer_guide.meta/voice_developer_guide/voice_rest_overview.htm)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.voice_developer_guide.meta/voice_developer_guide/voice_rest_authorization.htm)
- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.voice_pt_developer_guide.meta/voice_pt_developer_guide/voice_pt_dev_guide.htm)

### Salesforce Mobile SDK
The Salesforce Mobile SDK provides libraries and tools for building native and hybrid mobile applications on iOS and Android that integrate with the Salesforce platform.

**Human URL:** [https://developer.salesforce.com/docs/platform/mobile-sdk/overview](https://developer.salesforce.com/docs/platform/mobile-sdk/overview)

#### Tags:

 - Android, iOS, Mobile, React Native, SDK

#### Properties

- [Documentation](https://developer.salesforce.com/docs/platform/mobile-sdk/overview)
- [GettingStarted](https://developer.salesforce.com/docs/platform/mobile-sdk/guide/intro.html)
- [Portal](https://developer.salesforce.com/developer-centers/mobile)
- [GitHubRepository](https://github.com/forcedotcom/SalesforceMobileSDK-Android)

### Salesforce
Salesforce is a cloud-based customer relationship management (CRM) platform that helps organizations manage and grow customer relationships across the entire lifecycle.

**Human URL:** [https://developer.salesforce.com/](https://developer.salesforce.com/)

#### Tags:

 - CRM

#### Properties

- [Documentation](https://developer.salesforce.com/)
- [OpenAPI](openapi/salesforce-openapi.yml)

## Common Properties

- [Portal](https://developer.salesforce.com/)
- [Documentation](https://developer.salesforce.com/)
- [GettingStarted](https://trailhead.salesforce.com/)
- [StatusPage](https://status.salesforce.com/)
- [Support](https://help.salesforce.com/)
- [Community](https://trailblazers.salesforce.com/)
- [Authentication](https://help.salesforce.com/s/articleView?id=sf.remoteaccess_authenticate.htm)
- [OAuth Documentation](https://help.salesforce.com/s/articleView?id=sf.remoteaccess_oauth_flows.htm)
- [API Versions](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/dome_versions.htm)
- [Postman Collection](https://www.postman.com/salesforce-developers/)
- [GitHubOrganization](https://github.com/salesforce)
- [TermsOfService](https://www.salesforce.com/company/legal/agreements/)
- [PrivacyPolicy](https://www.salesforce.com/company/privacy/)
- [SignUp](https://login.salesforce.com/)
- [SignUp](https://developer.salesforce.com/signup)
- [Console](https://login.salesforce.com/)
- [Marketplace](https://appexchange.salesforce.com/)
- [Blog](https://developer.salesforce.com/blogs/)
- [SDK](https://developer.salesforce.com/tools/salesforcecli)
- [SDK](https://developer.salesforce.com/tools/)
- [ChangeLog](https://developer.salesforce.com/release-notes/)
- [StackOverflow](https://salesforce.stackexchange.com/)
- [Pricing](https://www.salesforce.com/pricing/)
- [X](https://twitter.com/salesforcedevs)
- [LinkedIn](https://www.linkedin.com/showcase/salesforce-developers)
- [YouTube](https://www.youtube.com/@salesforcedevelopers)
- [RateLimits](https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm)
- [Security](https://security.salesforce.com/security-advisories)
- [Security](https://developer.salesforce.com/developer-centers/security)
- [Security](https://developer.salesforce.com/docs/atlas.en-us.secure_coding_guide.meta/secure_coding_guide/secure_coding_guidelines.htm)
- [ReleaseNotes](https://help.salesforce.com/s/articleView?id=release-notes.salesforce_release_notes.htm&language=en_US)
- [Events](https://www.salesforce.com/events/)
- [Events](https://www.salesforce.com/dreamforce/)
- [Portal](https://developer.salesforce.com/developer-centers/integration-apis)
- [API Library](https://developer.salesforce.com/docs/apis)
- [Portal](https://developer.salesforce.com/developer-centers/mobile)
- [JSONLD](json-ld/salesforce-context.jsonld)
- [JSONSchema](json-schema/salesforce-sobject-schema.json)
- [JSONSchema](json-schema/salesforce-query-result-schema.json)
- [JSONSchema](json-schema/salesforce-bulk-job-schema.json)
- [JSONLD](json-ld/salesforce-rest-context.jsonld)
- [JSONLD](json-ld/salesforce-bulk-2-context.jsonld)
- [JSONLD](json-ld/salesforce-ui-context.jsonld)
- [SpectralRules](rules/salesforce-spectral-rules.yml)
- [Vocabulary](vocabulary/salesforce-vocabulary.yaml)
- [NaftikoCapability](capabilities/crm-data-management.yaml)
- [NaftikoCapability](capabilities/marketing-automation.yaml)
- [NaftikoCapability](capabilities/platform-administration.yaml)

## Features

| Name | Description |
|------|-------------|
| Multi-Cloud CRM Platform | Unified sales, service, marketing, and commerce applications accessible from a single cloud platform. |
| REST And SOAP APIs | Comprehensive REST and SOAP APIs for programmatic access to all Salesforce data and metadata. |
| Bulk Data Processing | Asynchronous bulk API for loading and querying millions of records in CSV format. |
| Real-Time Event Streaming | Pub/Sub and Streaming APIs for near-real-time event-driven integrations using platform events and change data capture. |
| AI-Powered Agents | Agentforce and Einstein APIs for building AI agents, predictions, and generative AI experiences. |
| GraphQL API | Modern GraphQL interface for efficient, client-driven queries against Salesforce data. |
| Marketing Cloud Automation | Programmatic access to journeys, contacts, data extensions, and transactional messaging. |
| Commerce APIs | B2B and B2C commerce APIs for storefronts, product catalogs, carts, and orders. |
| Custom Apex Endpoints | Build custom REST endpoints using Apex classes with full platform integration. |
| Composite And Batch Requests | Combine multiple API requests into a single call with dependent reference IDs for performance. |

## Use Cases

| Name | Description |
|------|-------------|
| CRM Data Integration | Synchronize customer, lead, and opportunity data between Salesforce and external systems. |
| Bulk Data Migration | Load and extract large volumes of records for data warehouse synchronization and ETL workflows. |
| Event-Driven Architecture | Build reactive integrations using platform events and change data capture for real-time data replication. |
| Marketing Campaign Orchestration | Automate multi-channel marketing journeys and manage subscriber engagement via Marketing Cloud APIs. |
| AI-Powered Customer Insights | Deploy Einstein predictions and Agentforce agents for intelligent lead scoring and customer service automation. |
| Custom Application Development | Build Lightning Web Components and custom Apex REST APIs to extend the Salesforce platform. |
| Commerce Storefront Integration | Power headless commerce experiences with shopper APIs for products, baskets, and orders. |
| DevOps And CI/CD Automation | Automate metadata deployments and manage org configurations using Metadata and Tooling APIs. |

## Integrations

| Name | Description |
|------|-------------|
| MuleSoft Anypoint | Native integration platform for connecting Salesforce with any application, data source, or API. |
| Tableau | Advanced analytics and data visualization through the Tableau REST API and Salesforce data connectors. |
| Slack | Embed Salesforce data and workflows into Slack channels for team collaboration. |
| Heroku | Deploy custom applications on Heroku with direct Salesforce data synchronization via Heroku Connect. |
| Amazon Web Services | AWS integrations for Service Cloud Voice with Amazon Connect and Data Cloud event bridges. |
| Google Cloud | BigQuery connectors and Google Workspace integrations for analytics and productivity. |
| Microsoft | Outlook and Teams integrations for email tracking, calendar sync, and collaborative selling. |
| AppExchange Partners | Thousands of pre-built integrations and applications available through the Salesforce AppExchange marketplace. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Salesforce Marketing Cloud REST OpenAPI](openapi/salesforce-marketing-cloud-rest-openapi.yml)
- [Salesforce OpenAPI](openapi/salesforce-openapi.yml)
- [Salesforce UI API OpenAPI](openapi/salesforce-ui-api-openapi.yml)
- [Salesforce REST API OpenAPI](openapi/salesforce-rest-api-openapi.yml)
- [Salesforce Bulk API 2 OpenAPI](openapi/salesforce-bulk-api-2-openapi.yml)

### AsyncAPI

- [Salesforce Change Data Capture AsyncAPI](asyncapi/salesforce-change-data-capture-asyncapi.yml)
- [Salesforce Platform Events AsyncAPI](asyncapi/salesforce-platform-events-asyncapi.yml)
- [Salesforce Streaming AsyncAPI](asyncapi/salesforce-streaming-asyncapi.yml)

### JSON-LD

- [Salesforce Context](json-ld/salesforce-context.jsonld)
- [Salesforce Bulk 2 Context](json-ld/salesforce-bulk-2-context.jsonld)
- [Salesforce REST Context](json-ld/salesforce-rest-context.jsonld)
- [Salesforce UI Context](json-ld/salesforce-ui-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Salesforce REST API](capabilities/shared/rest-api.yaml) -- 23 operations for SObject CRUD, SOQL, and SOSL
- [Salesforce Bulk API](capabilities/shared/bulk-api.yaml) -- 16 operations for bulk ingest and query jobs
- [Salesforce Marketing Cloud](capabilities/shared/marketing-cloud.yaml) -- 18 operations for contacts, journeys, and messaging
- [Salesforce UI API](capabilities/shared/ui-api.yaml) -- 10 operations for layouts, picklists, and list views
- [Salesforce Platform](capabilities/shared/salesforce.yaml) -- 14 operations for identity, OAuth, and metadata

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [CRM Data Management](capabilities/crm-data-management.yaml) | REST API, Bulk API 2.0, UI API | 32 | Salesforce admins, developers, and data teams |
| [Marketing Automation](capabilities/marketing-automation.yaml) | Marketing Cloud REST API | 16 | Marketing teams and marketing ops |
| [Platform Administration](capabilities/platform-administration.yaml) | Platform API, REST API, UI API | 8 | Salesforce admins and platform engineers |

## Vocabulary

- [Salesforce Vocabulary](vocabulary/salesforce-vocabulary.yaml) -- Unified taxonomy mapping 22 resources, 372 operations, and 1790 schemas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Salesforce Spectral Rules](rules/salesforce-spectral-rules.yml) -- 21 rules enforcing Salesforce API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
