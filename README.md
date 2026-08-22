# Azure DevOps (azure-devops)

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

Learn the basic patterns for using the REST APIs for Azure DevOps Services and Azure DevOps Server.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/azure-devops/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/azure-devops/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Azure
- CI/CD
- DevOps
- Pipelines
- Work Items

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Azure DevOps Work Item Tracking API

The Azure DevOps Work Item Tracking API provides REST endpoints for creating, updating, querying, and managing work items including bugs, tasks, user stories, epics, and features across Azure Boards. APIs support custom fields, area paths, iteration paths, and link types for Agile, Scrum, and CMMI process templates.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/azure/devops/](https://learn.microsoft.com/en-us/rest/api/azure/devops/)
- **Base URL:** `https://dev.azure.com/{organization}`

#### Tags

- Azure
- CI/CD
- DevOps
- Project Management
- Work Items

#### Properties

- [API Reference](https://learn.microsoft.com/en-us/rest/api/azure/devops/wit/?view=azure-devops-rest-7.2)
- [Getting Started](https://learn.microsoft.com/en-us/azure/devops/integrate/how-to/call-rest-api?view=azure-devops)
- [Authentication](https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance?view=azure-devops)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/azure-devops/refs/heads/main/openapi/azure-devops-work-items-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-devops-pipelines.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-devops-pipelines.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-devops-work-items.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-devops-work-items.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure DevOps Git Repositories API

The Azure DevOps Git Repositories API provides REST endpoints for managing Git repositories, branches, commits, pull requests, and code reviews. APIs enable automation of repository management, pull request workflows, branch policies, and code review processes within Azure Repos.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/azure/devops/](https://learn.microsoft.com/en-us/rest/api/azure/devops/)
- **Base URL:** `https://dev.azure.com/{organization}`

#### Tags

- Azure
- CI/CD
- DevOps
- Git
- Pull Requests
- Version Control

#### Properties

- [API Reference](https://learn.microsoft.com/en-us/rest/api/azure/devops/git/?view=azure-devops-rest-7.2)
- [Getting Started](https://learn.microsoft.com/en-us/azure/devops/integrate/how-to/call-rest-api?view=azure-devops)
- [Authentication](https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance?view=azure-devops)
- [Postman Collection](collections/azure-devops-pipelines.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-devops-pipelines.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-devops-work-items.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-devops-work-items.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure DevOps Pipelines API

The Azure DevOps Pipelines API provides REST endpoints for managing CI/CD build and release pipelines. APIs support pipeline creation, triggering builds, retrieving build results, managing release definitions, and automating deployment workflows across Azure DevOps organizations.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/azure/devops/](https://learn.microsoft.com/en-us/rest/api/azure/devops/)
- **Base URL:** `https://dev.azure.com/{organization}`

#### Tags

- Azure
- Build
- CI/CD
- DevOps
- Pipelines
- Release

#### Properties

- [API Reference](https://learn.microsoft.com/en-us/rest/api/azure/devops/pipelines/?view=azure-devops-rest-7.2)
- [Getting Started](https://learn.microsoft.com/en-us/azure/devops/integrate/how-to/call-rest-api?view=azure-devops)
- [Authentication](https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance?view=azure-devops)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/azure-devops/refs/heads/main/openapi/azure-devops-pipelines-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/azure-devops-pipelines.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-devops-pipelines.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-devops-work-items.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-devops-work-items.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure DevOps Artifacts API

The Azure DevOps Artifacts API provides REST endpoints for managing package feeds including NuGet, npm, Maven, Python, and Universal Packages. APIs support feed creation, package publishing, version management, and upstream source configuration for artifact management in DevOps workflows.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/azure/devops/](https://learn.microsoft.com/en-us/rest/api/azure/devops/)
- **Base URL:** `https://pkgs.dev.azure.com/{organization}`

#### Tags

- Artifacts
- Azure
- CI/CD
- DevOps
- Npm
- NuGet
- Package Management

#### Properties

- [API Reference](https://learn.microsoft.com/en-us/rest/api/azure/devops/artifacts/?view=azure-devops-rest-7.2)
- [Getting Started](https://learn.microsoft.com/en-us/azure/devops/integrate/how-to/call-rest-api?view=azure-devops)
- [Postman Collection](collections/azure-devops-pipelines.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-devops-pipelines.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-devops-work-items.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-devops-work-items.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure DevOps Test Plans API

The Azure DevOps Test Plans API provides REST endpoints for managing test plans, test suites, test cases, and test runs. APIs support automated test management, test result reporting, and integration with CI/CD pipelines for comprehensive quality assurance workflows.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/azure/devops/](https://learn.microsoft.com/en-us/rest/api/azure/devops/)
- **Base URL:** `https://dev.azure.com/{organization}`

#### Tags

- Azure
- CI/CD
- DevOps
- Test Plans
- Testing

#### Properties

- [API Reference](https://learn.microsoft.com/en-us/rest/api/azure/devops/testplan/?view=azure-devops-rest-7.2)
- [Getting Started](https://learn.microsoft.com/en-us/azure/devops/integrate/how-to/call-rest-api?view=azure-devops)
- [Postman Collection](collections/azure-devops-pipelines.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-devops-pipelines.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-devops-work-items.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-devops-work-items.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure DevOps Release API

The Azure DevOps Release API provides REST endpoints for managing release pipelines, deployments, and environments. APIs support release definition management, deployment approvals, environment configuration, and release history tracking for continuous delivery workflows.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/azure/devops/](https://learn.microsoft.com/en-us/rest/api/azure/devops/)
- **Base URL:** `https://vsrm.dev.azure.com/{organization}`

#### Tags

- Azure
- CI/CD
- Deployment
- DevOps
- Release Management

#### Properties

- [API Reference](https://learn.microsoft.com/en-us/rest/api/azure/devops/release/?view=azure-devops-rest-7.1)
- [Getting Started](https://learn.microsoft.com/en-us/azure/devops/integrate/how-to/call-rest-api?view=azure-devops)
- [Postman Collection](collections/azure-devops-pipelines.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-devops-pipelines.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-devops-work-items.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-devops-work-items.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/microsoft-azure-devops)
- [Documentation](https://azure.microsoft.com/en-us/products/devops)
- [Portal](https://learn.microsoft.com/en-us/rest/api/azure/devops/)
- [API Reference](https://learn.microsoft.com/en-us/rest/api/azure/devops/?view=azure-devops-rest-7.2)
- [Getting Started](https://learn.microsoft.com/en-us/azure/devops/integrate/how-to/call-rest-api?view=azure-devops)
- [Authentication](https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance?view=azure-devops)
- [Rate Limits](https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/rate-limits?view=azure-devops)
- [Changelog](https://learn.microsoft.com/en-us/azure/devops/release-notes/features-timeline-released)
- [Documentation](https://learn.microsoft.com/en-us/azure/devops/dev-resources/?view=azure-devops)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [GitHub Organization](https://github.com/microsoft)
- [SDK](https://github.com/microsoft/azure-devops-node-api)
- [SDK](https://github.com/microsoft/azure-devops-python-api)
- [SDK](https://github.com/microsoft/azure-devops-go-api)
- [SDK](https://github.com/microsoft/azure-devops-java-api)
- [C L I](https://github.com/Azure/azure-devops-cli-extension)
- [OpenAPI](openapi/azure-devops-work-items-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/azure-devops-pipelines-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/azure-devops-pipelines-create-pipeline-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-devops-pipelines-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-devops-pipelines-pipeline-run-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-devops-pipelines-pipeline-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-devops-pipelines-run-pipeline-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-devops-work-items-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-devops-work-items-json-patch-operation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-devops-work-items-wiql-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-devops-work-items-work-item-field-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-devops-work-items-work-item-relation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-devops-work-items-work-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/azure-devops-workitem-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/azure-devops-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/azure-devops-pipelines-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/azure-devops-work-items-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/azure-devops-vocabulary.yaml)
- [Rules](rules/azure-devops-spectral-rules.yml)
- [Capabilities](capabilities/devops-project-management.yaml)
- [Capabilities](capabilities/shared/work-items.yaml)
- [Capabilities](capabilities/shared/pipelines.yaml)
- [M C P Server](https://github.com/microsoft/azure-devops-mcp)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
