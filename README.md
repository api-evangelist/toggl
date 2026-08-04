# Toggl Track (toggl)

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

Toggl Track is a time-tracking and productivity platform for freelancers, teams, and agencies that captures billable hours, project time, and team capacity across web, desktop, mobile, and browser extension clients. The product offers automated tracking, calendar integration, custom reporting, 100+ integrations (Jira, Salesforce, Asana, GitHub), and supports billing, payroll, and project profitability use cases. The Toggl Track API v9 is a REST interface for time entries, workspaces, projects, clients, users, and reports using HTTP Basic Authentication with an API token.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/toggl/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/toggl/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Time Tracking
- Productivity
- Project Management
- Billing
- Reporting
- Workforce Management

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Toggl Track API v9

Current REST API for managing time entries, workspaces, projects, clients, tags, tasks, users, and organizations in Toggl Track. Authentication uses HTTP Basic Auth with the API token as username and the literal "api_token" as password.

- **Human URL:** [https://engineering.toggl.com/docs/](https://engineering.toggl.com/docs/)
- **Base URL:** `https://api.track.toggl.com/api/v9`

#### Tags

- Time Tracking
- Time Entries
- Projects
- Workspaces
- Users

#### Properties

- [Documentation](https://engineering.toggl.com/docs/)
- [Authentication](https://engineering.toggl.com/docs/authentication)
- [API Reference](https://engineering.toggl.com/docs/api/me)
- [Postman Collection](collections/toggl.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toggl.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Toggl Track Reports API v3

Reporting API for generating detailed, summary, and weekly reports across time entries, with support for filtering, grouping, and export formats (JSON, CSV, PDF).

- **Human URL:** [https://engineering.toggl.com/docs/reports_start](https://engineering.toggl.com/docs/reports_start)
- **Base URL:** `https://api.track.toggl.com/reports/api/v3`

#### Tags

- Reports
- Analytics
- Exports

#### Properties

- [Documentation](https://engineering.toggl.com/docs/reports_start)
- [Postman Collection](collections/toggl.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toggl.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Toggl Track Webhooks API

Webhooks API for subscribing to events such as time entry creation, updates, deletions, and project changes within a workspace.

- **Human URL:** [https://engineering.toggl.com/docs/webhooks_start](https://engineering.toggl.com/docs/webhooks_start)
- **Base URL:** `https://api.track.toggl.com/webhooks/api/v1`

#### Tags

- Webhooks
- Events

#### Properties

- [Documentation](https://engineering.toggl.com/docs/webhooks_start)
- [Postman Collection](collections/toggl.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toggl.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/toggl)
- [Website](https://toggl.com/track/)
- [Developer  Portal](https://engineering.toggl.com/docs/)
- [Documentation](https://engineering.toggl.com/docs/)
- [Pricing](https://toggl.com/track/pricing/)
- [Sign Up](https://toggl.com/track/signup/)
- [Login](https://track.toggl.com/login)
- [Blog](https://toggl.com/blog/)
- [Support](https://support.toggl.com/en/)
- [Community](https://community.toggl.com/)
- [GitHub Organization](https://github.com/toggl)
- [Status Page](https://status.toggl.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
