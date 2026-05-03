# Snowplow

Snowplow is a behavioral data platform that enables organizations to collect, process, and model granular event-level data from web, mobile, and server-side sources. The platform uses a schema-first approach with self-describing JSON events validated against the Iglu schema registry. The Snowplow Console API provides programmatic governance of data structures (schemas), data products (tracking plans), and event specifications.

## APIs

- [Snowplow Console API](https://docs.snowplow.io/docs/event-studio/programmatic-management/) - Programmatic management of data structures (event schemas), data products (tracking plans), event specifications, and credentials via REST API.
- [Snowplow Tracker SDKs](https://docs.snowplow.io/docs/collecting-data/collecting-from-own-applications) - Tracker SDKs for JavaScript, iOS, Android, Python, Java, Go, Ruby, .NET, PHP, and Rust.

## Properties

- [Website](https://snowplow.io)
- [Documentation](https://docs.snowplow.io)
- [GitHub Organization](https://github.com/snowplow)
- [Console](https://console.snowplowanalytics.com)
- [Community](https://discourse.snowplow.io)
- [Swagger UI](https://console.snowplowanalytics.com/api/msc/v1/docs/)

## Artifacts

### OpenAPI
- [snowplow-console-api-openapi.yml](openapi/snowplow-console-api-openapi.yml) — Snowplow Console API (Authentication, Data Structures, Data Products, Deployment)

### Rules
- [snowplow-rules.yml](rules/snowplow-rules.yml) — Spectral ruleset enforcing Snowplow Console API conventions (org-scoped paths, versioned resources, JWT auth)

### Capabilities
- [data-pipeline-governance.yaml](capabilities/data-pipeline-governance.yaml) — Unified workflow for Snowplow schema lifecycle management and tracking plan governance

#### Shared Definitions
- [capabilities/shared/console-api.yaml](capabilities/shared/console-api.yaml) — Snowplow Console API shared capability definition

### JSON Schema
- [snowplow-event-schema.json](json-schema/snowplow-event-schema.json) — Schema for enriched Snowplow behavioral events (all standard fields)
- [snowplow-data-structure-schema.json](json-schema/snowplow-data-structure-schema.json) — Schema for Snowplow data structure (event schema) management objects

### JSON Structure
- [snowplow-pipeline-structure.json](json-structure/snowplow-pipeline-structure.json) — Hierarchical structure of Snowplow data pipeline components from tracker to data warehouse

### JSON-LD
- [snowplow-context.jsonld](json-ld/snowplow-context.jsonld) — JSON-LD context for Snowplow behavioral data and event tracking linked data semantics

### Examples
- [snowplow-list-data-structures-example.json](examples/snowplow-list-data-structures-example.json) — List event schemas (data structures) in a Snowplow organization
- [snowplow-deploy-data-structure-example.json](examples/snowplow-deploy-data-structure-example.json) — Deploy a validated event schema to the PROD environment

### Vocabulary
- [snowplow-vocabulary.yml](vocabulary/snowplow-vocabulary.yml) — Domain vocabulary covering Snowplow events, trackers, enrichments, Iglu schemas, and data governance concepts
