# Azure DevOps (azure-devops)

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
