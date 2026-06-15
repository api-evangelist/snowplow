# Snowplow (snowplow)

Snowplow is a behavioral data platform that enables organizations to collect, process, and model granular event-level data from web, mobile, and server-side sources, providing a data pipeline for analytics and AI use cases. The platform uses a schema-first approach with self-describing JSON events validated against the Iglu schema registry. The Snowplow Console API provides programmatic governance of data structures (schemas), data products (tracking plans), and event specifications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/snowplow/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/snowplow/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Analytics Platform
- Behavioral Data
- Data Collection
- Data Engineering
- Data Pipeline
- Event Tracking
- Open Source

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-19

## APIs

### Snowplow Console API

The Snowplow Console API provides programmatic management of the Snowplow behavioral data platform. Covers data structures (JSON schemas for event validation), data products (tracking plans), event specifications, and credentials. All endpoints are scoped to an organization and require JWT bearer authentication. Accessible via Swagger UI at https://console.snowplowanalytics.com/api/msc/v1/docs/.

- **Human URL:** [https://docs.snowplow.io/docs/event-studio/programmatic-management/](https://docs.snowplow.io/docs/event-studio/programmatic-management/)

#### Tags

- Analytics Platform
- Data Governance
- Data Structures
- Schema Management

#### Properties

- [Documentation](https://docs.snowplow.io/docs/event-studio/programmatic-management/)
- [Swagger U I](https://console.snowplowanalytics.com/api/msc/v1/docs/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/snowplow/refs/heads/main/openapi/snowplow-console-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/snowplow-console-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snowplow-console-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Snowplow Tracker SDKs

Snowplow provides tracker SDKs for all major platforms including JavaScript (web), iOS, Android, Python, Java, Go, Ruby, .NET, PHP, and Rust. Trackers generate self-describing events and send them to the Snowplow Collector. All trackers support self-describing events, contexts, page views, structured events, and session tracking.

- **Human URL:** [https://docs.snowplow.io/docs/collecting-data/collecting-from-own-applications](https://docs.snowplow.io/docs/collecting-data/collecting-from-own-applications)

#### Tags

- Analytics
- Event Tracking
- SDK

#### Properties

- [Documentation](https://docs.snowplow.io/docs/collecting-data/collecting-from-own-applications)
- [Git Hub Org](https://github.com/snowplow)
- [Postman Collection](collections/snowplow-console-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/snowplow-console-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/snowplow)
- [Website](https://snowplow.io)
- [Documentation](https://docs.snowplow.io)
- [Blog](https://snowplow.io/blog)
- [Pricing](https://snowplow.io/pricing)
- [Git Hub](https://github.com/snowplow)
- [Login](https://console.snowplowanalytics.com)
- [Sign Up](https://snowplow.io/get-started)
- [Support](https://snowplow.io/support)
- [Getting Started](https://docs.snowplow.io/docs/getting-started-on-snowplow-open-source)
- [Community](https://discourse.snowplow.io)
- [Data Structures A P I](https://docs.snowplow.io/docs/data-product-studio/data-structures/manage/api/)
- [Tracking Plans A P I](https://docs.snowplow.io/docs/data-product-studio/data-products/api/)
- [Credentials A P I](https://docs.snowplow.io/docs/account-management/)
- [Integrations](https://snowplow.io/partners)
- [L L Ms Txt](https://docs.snowplow.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
