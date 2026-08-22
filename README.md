# Conduktor (conduktor)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
