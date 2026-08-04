# Codacy (codacy)

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
