# Codacy (codacy)

Codacy is an automated code quality and security platform that analyzes commits and pull requests across 49+ languages, surfacing issues, coverage, and security findings. The Codacy API v3 lets teams manage organizations, repositories, issues, pull requests, coverage, security, and quality settings programmatically.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/codacy/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/codacy/refs/heads/main/apis.yml)

## Tags

- Code Quality
- Static Analysis
- Security
- Code Coverage
- DevOps

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Codacy Organizations API

List and inspect the Git provider organizations a Codacy account belongs to, manage join requests, and retrieve organization-level analysis context across GitHub, GitLab, and Bitbucket.

- **Human URL:** [https://docs.codacy.com/codacy-api/using-the-codacy-api/](https://docs.codacy.com/codacy-api/using-the-codacy-api/)
- **Base URL:** `https://api.codacy.com/api/v3`

#### Tags

- Organizations
- Accounts

#### Properties

- [Documentation](https://docs.codacy.com/codacy-api/using-the-codacy-api/)
- [API Reference](https://api.codacy.com/api/api-docs)
- [OpenAPI](openapi/codacy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/codacy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/codacy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Codacy Repositories API

Add, follow, unfollow, and synchronize repositories with their Git provider, and retrieve per-repository analysis state including the first-analysis progress overview.

- **Human URL:** [https://docs.codacy.com/codacy-api/examples/adding-repositories-to-codacy-programmatically/](https://docs.codacy.com/codacy-api/examples/adding-repositories-to-codacy-programmatically/)
- **Base URL:** `https://api.codacy.com/api/v3`

#### Tags

- Repositories
- Analysis

#### Properties

- [Documentation](https://docs.codacy.com/codacy-api/examples/adding-repositories-to-codacy-programmatically/)
- [API Reference](https://api.codacy.com/api/api-docs)
- [OpenAPI](openapi/codacy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/codacy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/codacy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Codacy Issues API

Search repository issues by category and severity, view an issues overview, update issue state, ignore false positives, and bulk-ignore issues surfaced by static analysis.

- **Human URL:** [https://docs.codacy.com/codacy-api/examples/obtaining-current-issues-in-repositories/](https://docs.codacy.com/codacy-api/examples/obtaining-current-issues-in-repositories/)
- **Base URL:** `https://api.codacy.com/api/v3`

#### Tags

- Issues
- Static Analysis
- Quality

#### Properties

- [Documentation](https://docs.codacy.com/codacy-api/examples/obtaining-current-issues-in-repositories/)
- [API Reference](https://api.codacy.com/api/api-docs)
- [OpenAPI](openapi/codacy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/codacy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/codacy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Codacy Pull Requests API

List and inspect pull requests with their analysis results, files, issues, and commits, trigger the AI Reviewer, and bypass pull-request analysis gates across an organization.

- **Human URL:** [https://docs.codacy.com/codacy-api/using-the-codacy-api/](https://docs.codacy.com/codacy-api/using-the-codacy-api/)
- **Base URL:** `https://api.codacy.com/api/v3`

#### Tags

- Pull Requests
- Code Review
- AI Reviewer

#### Properties

- [Documentation](https://docs.codacy.com/codacy-api/using-the-codacy-api/)
- [API Reference](https://api.codacy.com/api/api-docs)
- [OpenAPI](openapi/codacy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/codacy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/codacy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Codacy Coverage API

Retrieve code coverage for pull requests and individual files, inspect coverage report status, and trigger coverage reanalysis for a repository pull request.

- **Human URL:** [https://docs.codacy.com/coverage-reporter/](https://docs.codacy.com/coverage-reporter/)
- **Base URL:** `https://api.codacy.com/api/v3`

#### Tags

- Code Coverage
- Pull Requests
- Reports

#### Properties

- [Documentation](https://docs.codacy.com/coverage-reporter/)
- [API Reference](https://api.codacy.com/api/api-docs)
- [OpenAPI](openapi/codacy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/codacy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/codacy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Codacy Security API

Manage repository quality and security gating settings for commits and pull requests, and administer repository SSH keys used for secure source access.

- **Human URL:** [https://docs.codacy.com/organizations/security-monitor/](https://docs.codacy.com/organizations/security-monitor/)
- **Base URL:** `https://api.codacy.com/api/v3`

#### Tags

- Security
- SAST
- Quality Settings

#### Properties

- [Documentation](https://docs.codacy.com/organizations/security-monitor/)
- [API Reference](https://api.codacy.com/api/api-docs)
- [OpenAPI](openapi/codacy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/codacy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/codacy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/codacy)
- [LinkedIn](https://www.linkedin.com/company/codacy)
- [Website](https://www.codacy.com)
- [Documentation](https://docs.codacy.com)
- [Plans](plans/codacy-plans-pricing.yml)
- [Rate Limits](rate-limits/codacy-rate-limits.yml)
- [Fin Ops](finops/codacy-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
