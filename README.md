# Conduktor (conduktor)

Conduktor is an Apache Kafka management and data-governance platform. Conduktor Console provides a REST API and CLI to manage clusters, topics, consumer groups, certificates, users, groups, and granular RBAC, plus declarative Self-Service resources (Application, ApplicationInstance, TopicPolicy). Conduktor Gateway is a Kafka proxy with a REST API for interceptors (data security, quality, governance) and virtual clusters.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/conduktor/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/conduktor/refs/heads/main/apis.yml)

## Tags

- Apache Kafka
- Streaming
- Data Governance
- Kafka Management
- Gateway

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Conduktor Console - Clusters, Topics & Consumer Groups API

Register and manage Kafka clusters and their certificates, and inspect cluster resources such as topics and consumer groups through the Conduktor Console REST API, authenticated with an admin-generated Bearer API key.

- **Human URL:** [https://docs.conduktor.io/platform/reference/api-reference/](https://docs.conduktor.io/platform/reference/api-reference/)
- **Base URL:** `https://{console-host}/public/console/v1`

#### Tags

- Clusters
- Topics
- Consumer Groups

#### Properties

- [Documentation](https://docs.conduktor.io/platform/reference/api-reference/)
- [API Reference](https://developers.conduktor.io/?product=console)
- [OpenAPI](openapi/conduktor-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/conduktor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/conduktor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Conduktor Console - RBAC & Users API

Manage organization users, groups, and granular role-based access control permissions that can be scoped to one cluster or all clusters, via the Conduktor Console IAM endpoints.

- **Human URL:** [https://docs.conduktor.io/platform/admin/rbac/](https://docs.conduktor.io/platform/admin/rbac/)
- **Base URL:** `https://{console-host}/public/iam/v2`

#### Tags

- RBAC
- Users
- Groups

#### Properties

- [Documentation](https://docs.conduktor.io/platform/admin/rbac/)
- [API Reference](https://developers.conduktor.io/?product=console)
- [OpenAPI](openapi/conduktor-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/conduktor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/conduktor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Conduktor Console - Self-Service API

Declaratively manage Self-Service resources - Application, ApplicationInstance, and TopicPolicy - so platform teams can enforce naming and configuration standards while application teams own their topic lifecycle as code.

- **Human URL:** [https://docs.conduktor.io/platform/reference/resource-reference/self-service/](https://docs.conduktor.io/platform/reference/resource-reference/self-service/)
- **Base URL:** `https://{console-host}/public/self-serve/v1`

#### Tags

- Self-Service
- Topic Policies
- Infrastructure as Code

#### Properties

- [Documentation](https://docs.conduktor.io/platform/reference/resource-reference/self-service/)
- [API Reference](https://developers.conduktor.io/?product=console)
- [OpenAPI](openapi/conduktor-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/conduktor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/conduktor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Conduktor Gateway - Interceptors API

Create, list, and delete Gateway interceptors that apply data security, data quality, governance, and observability policies to Kafka traffic, via the Conduktor Gateway admin REST API using Basic authentication.

- **Human URL:** [https://docs.conduktor.io/gateway/](https://docs.conduktor.io/gateway/)
- **Base URL:** `https://{gateway-admin-host}:8888/gateway/v2`

#### Tags

- Gateway
- Interceptors
- Data Security

#### Properties

- [Documentation](https://docs.conduktor.io/gateway/)
- [API Reference](https://developers.conduktor.io/?product=gateway)
- [OpenAPI](openapi/conduktor-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/conduktor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/conduktor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Conduktor Gateway - Virtual Clusters API

Provision and manage Gateway virtual clusters for multi-tenancy, along with their service accounts and authentication tokens, through the Conduktor Gateway admin REST API.

- **Human URL:** [https://docs.conduktor.io/gateway/how-to/multi-cluster/](https://docs.conduktor.io/gateway/how-to/multi-cluster/)
- **Base URL:** `https://{gateway-admin-host}:8888/gateway/v2`

#### Tags

- Gateway
- Virtual Clusters
- Multi-Tenancy

#### Properties

- [Documentation](https://docs.conduktor.io/gateway/how-to/multi-cluster/)
- [API Reference](https://developers.conduktor.io/?product=gateway)
- [OpenAPI](openapi/conduktor-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/conduktor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/conduktor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/conduktor)
- [LinkedIn](https://www.linkedin.com/company/conduktor)
- [Website](https://www.conduktor.io)
- [Documentation](https://docs.conduktor.io)
- [Plans](plans/conduktor-plans-pricing.yml)
- [Rate Limits](rate-limits/conduktor-rate-limits.yml)
- [Fin Ops](finops/conduktor-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
