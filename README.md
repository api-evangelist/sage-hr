# Sage HR (sage-hr)

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

Sage HR (formerly CakeHR) is a cloud HRIS for small and mid-sized businesses, owned by Sage Group plc. It bundles core HR records, leave management, performance, recruitment (ATS), timesheets, shift scheduling, expenses, and onboarding/offboarding into a modular per-employee SaaS. The Sage HR REST API at apidoc.sage.hr exposes 53 operations across employees, leave, recruitment, performance, timesheets, documents, onboarding, offboarding, organization, and a Vikarina payroll integration bridge. Authentication is a tenant-scoped X-Auth-Token API key against the customer's own subdomain (https://{subdomain}.sage.hr/api).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sage-hr/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sage-hr/refs/heads/main/apis.yml)

## Scope

- **Access:** 3rd-Party

## Tags

- HR
- HRIS
- People
- SMB
- Leave Management
- Recruitment
- Performance
- Timesheets
- Onboarding

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Sage HR Employee API

Manage the employee directory in Sage HR — list active and terminated employees, fetch an employee by ID, create new employees, update employee records and custom fields, retrieve compensation history, and process terminations. Backed by the /employees and /terminated-employees resource trees.

- **Human URL:** [https://apidoc.sage.hr/](https://apidoc.sage.hr/)

#### Tags

- HR
- HRIS
- Employees
- People

#### Properties

- [Documentation](https://apidoc.sage.hr/)
- [OpenAPI](openapi/sage-hr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sage-hr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sage-hr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/sage-hr-employee-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/sage-hr-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Sage HR Leave Management API

Manage employee leave in Sage HR — list and inspect time-off policies, manage KIT (Keeping In Touch) days, query individual allowances and per-employee balances, list and create time-off requests, and retrieve the list of employees out of office today.

- **Human URL:** [https://apidoc.sage.hr/](https://apidoc.sage.hr/)

#### Tags

- HR
- Leave
- Time Off
- PTO
- Policies

#### Properties

- [Documentation](https://apidoc.sage.hr/)
- [OpenAPI](openapi/sage-hr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sage-hr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sage-hr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sage HR Recruitment API

Sage HR's applicant tracking surface — list open recruitment positions, fetch position details, list and create applicants (including referrals), pull applicant detail records, and list pipeline actions against an applicant.

- **Human URL:** [https://apidoc.sage.hr/](https://apidoc.sage.hr/)

#### Tags

- HR
- Recruitment
- ATS
- Applicants
- Hiring

#### Properties

- [Documentation](https://apidoc.sage.hr/)
- [OpenAPI](openapi/sage-hr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sage-hr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sage-hr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sage HR Performance API

Quarterly performance and goal reporting — overall quarterly progress overview plus drill-down endpoints for company-wide goals, team goals, and individual employee goals.

- **Human URL:** [https://apidoc.sage.hr/](https://apidoc.sage.hr/)

#### Tags

- HR
- Performance
- Goals
- OKRs

#### Properties

- [Documentation](https://apidoc.sage.hr/)
- [OpenAPI](openapi/sage-hr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sage-hr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sage-hr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sage HR Timesheets API

Programmatic clock-in / clock-out for Sage HR Timesheets via /timesheets/clock-in. Lets integrations capture punch events for time-tracked employees.

- **Human URL:** [https://apidoc.sage.hr/](https://apidoc.sage.hr/)

#### Tags

- HR
- Timesheets
- Time Tracking
- Clock In

#### Properties

- [Documentation](https://apidoc.sage.hr/)
- [OpenAPI](openapi/sage-hr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sage-hr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sage-hr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sage HR Onboarding and Offboarding API

List task categories and create onboarding and offboarding tasks for an employee lifecycle workflow. Backs /onboarding/categories, /onboarding/tasks, /offboarding/categories, and /offboarding/tasks.

- **Human URL:** [https://apidoc.sage.hr/](https://apidoc.sage.hr/)

#### Tags

- HR
- Onboarding
- Offboarding
- Tasks

#### Properties

- [Documentation](https://apidoc.sage.hr/)
- [OpenAPI](openapi/sage-hr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sage-hr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sage-hr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sage HR Documents API

List document categories and upload new employee or company documents to Sage HR. Multipart form-data upload via /documents.

- **Human URL:** [https://apidoc.sage.hr/](https://apidoc.sage.hr/)

#### Tags

- HR
- Documents
- Files

#### Properties

- [Documentation](https://apidoc.sage.hr/)
- [OpenAPI](openapi/sage-hr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sage-hr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sage-hr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sage HR Organization API

Inspect the org structure — list company positions, list teams, and list available termination reasons. Read-only endpoints used to drive directory and dropdown surfaces in client apps.

- **Human URL:** [https://apidoc.sage.hr/](https://apidoc.sage.hr/)

#### Tags

- HR
- Positions
- Teams
- Organization
- Terminations

#### Properties

- [Documentation](https://apidoc.sage.hr/)
- [OpenAPI](openapi/sage-hr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sage-hr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sage-hr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sage HR Vikarina Integrations API

Sage HR → Vikarina payroll bridge. Transfer job positions, organizational structure, new-starter lists, contract information, appointments, salaries, bank accounts, terminations, unused vacation days, leave types, timesheets, and bonuses from Sage HR into Vikarina.

- **Human URL:** [https://apidoc.sage.hr/](https://apidoc.sage.hr/)

#### Tags

- HR
- Integrations
- Vikarina
- Payroll

#### Properties

- [Documentation](https://apidoc.sage.hr/)
- [OpenAPI](openapi/sage-hr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sage-hr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sage-hr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://sage.hr/)
- [Portal](https://www.sage.com/en-gb/sage-business-cloud/hr/)
- [Documentation](https://apidoc.sage.hr/)
- [Documentation](https://support.sage.hr/en/articles/3246469-how-does-cakehr-api-work)
- [Support](https://support.sage.hr/)
- [Pricing](https://sage.hr/pricing/)
- [Integrations](https://sage.hr/integrations/)
- [LinkedIn](https://www.linkedin.com/company/sage-hr/)
- [Twitter](https://twitter.com/sagehr)
- [Git Hub](https://github.com/Sage)
- [Plans](plans/sage-hr-plans-pricing.yml)
- [Rate Limits](rate-limits/sage-hr-rate-limits.yml)
- [Fin Ops](finops/sage-hr-finops.yml)
