# Sage HR

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

**Areas:** Human Resources · HRIS · People · Small Business · Leave Management · Recruiting · Performance · Timesheets · Onboarding

## Sage HR on APIs.io

Everything profiled for Sage HR is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/sage-hr/](https://apis.io/providers/sage-hr/)** — or go straight to one of the APIs or properties below.

### APIs (14)

- [Sage HR Documents API](https://apis.io/apis/sage-hr/sage-hr-documents-api/) — The Documents API from Sage HR — 2 operation(s) for documents.
- [Sage HR Employee API](https://apis.io/apis/sage-hr/sage-hr-employee-api/) — The Employee API from Sage HR — 9 operation(s) for employee.
- [Sage HR Integrations API](https://apis.io/apis/sage-hr/sage-hr-integrations-api/) — The Integrations API from Sage HR — 12 operation(s) for integrations.
- [Sage HR KIT days API](https://apis.io/apis/sage-hr/sage-hr-kit-days-api/) — The KIT days API from Sage HR — 3 operation(s) for kit days.
- [Sage HR Leave management API](https://apis.io/apis/sage-hr/sage-hr-leave-management-api/) — The Leave management API from Sage HR — 8 operation(s) for leave management.
- [Sage HR Offboarding API](https://apis.io/apis/sage-hr/sage-hr-offboarding-api/) — The Offboarding API from Sage HR — 2 operation(s) for offboarding.
- [Sage HR Onboarding API](https://apis.io/apis/sage-hr/sage-hr-onboarding-api/) — The Onboarding API from Sage HR — 2 operation(s) for onboarding.
- [Sage HR Performance API](https://apis.io/apis/sage-hr/sage-hr-performance-api/) — The Performance API from Sage HR — 4 operation(s) for performance.
- [Sage HR Policies API](https://apis.io/apis/sage-hr/sage-hr-policies-api/) — The Policies API from Sage HR — 2 operation(s) for policies.
- [Sage HR Positions API](https://apis.io/apis/sage-hr/sage-hr-positions-api/) — The Positions API from Sage HR — 1 operation(s) for positions.
- [Sage HR Recruitment API](https://apis.io/apis/sage-hr/sage-hr-recruitment-api/) — The Recruitment API from Sage HR — 5 operation(s) for recruitment.
- [Sage HR Teams API](https://apis.io/apis/sage-hr/sage-hr-teams-api/) — The Teams API from Sage HR — 1 operation(s) for teams.
- [Sage HR Terminations reasons API](https://apis.io/apis/sage-hr/sage-hr-terminations-reasons-api/) — The Terminations reasons API from Sage HR — 1 operation(s) for terminations reasons.
- [Sage HR Timesheets API](https://apis.io/apis/sage-hr/sage-hr-timesheets-api/) — The Timesheets API from Sage HR — 1 operation(s) for timesheets.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Sage Hr Agentic Access](https://apis.io/agentic-access/sage-hr/sage-hr-agentic-access/)

#### JSON Schema (1)

The data models the API reads and writes.

- [Sage HR Employee](https://apis.io/schemas/sage-hr/sage-hr-employee/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Sage Hr Context](https://apis.io/jsonld/sage-hr/sage-hr-context/)

#### Collections (15)

Postman and Open Collection request collections.

- [Sage HR API](https://apis.io/collections/sage-hr/open-sage-hr/)
- [Sage HR Documents API](https://apis.io/collections/sage-hr/open-sage-hr-documents-api/)
- [Sage HR Documents Employee API](https://apis.io/collections/sage-hr/open-sage-hr-employee-api/)
- [Sage HR Documents Integrations API](https://apis.io/collections/sage-hr/open-sage-hr-integrations-api/)
- [Sage HR Documents KIT days API](https://apis.io/collections/sage-hr/open-sage-hr-kit-days-api/)
- [Sage HR Documents Leave management API](https://apis.io/collections/sage-hr/open-sage-hr-leave-management-api/)
- [Sage HR Documents Offboarding API](https://apis.io/collections/sage-hr/open-sage-hr-offboarding-api/)
- [Sage HR Documents Onboarding API](https://apis.io/collections/sage-hr/open-sage-hr-onboarding-api/)
- [Sage HR Documents Performance API](https://apis.io/collections/sage-hr/open-sage-hr-performance-api/)
- [Sage HR Documents Policies API](https://apis.io/collections/sage-hr/open-sage-hr-policies-api/)
- [Sage HR Documents Positions API](https://apis.io/collections/sage-hr/open-sage-hr-positions-api/)
- [Sage HR Documents Recruitment API](https://apis.io/collections/sage-hr/open-sage-hr-recruitment-api/)
- [Sage HR Documents Teams API](https://apis.io/collections/sage-hr/open-sage-hr-teams-api/)
- [Sage HR Documents Terminations reasons API](https://apis.io/collections/sage-hr/open-sage-hr-terminations-reasons-api/)
- [Sage HR Documents Timesheets API](https://apis.io/collections/sage-hr/open-sage-hr-timesheets-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Sage HR — jsonschema rules](https://apis.io/rules/sage-hr/sage-hr-jsonschema-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Sage Hr Authentication](https://apis.io/security/sage-hr/sage-hr-authentication/)
- [Sage Hr Domain Security](https://apis.io/security/sage-hr/sage-hr-domain-security/)
- [Sage Hr Vulnerability Disclosure](https://apis.io/security/sage-hr/sage-hr-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Sage Hr Plans Pricing](https://apis.io/plans/sage-hr/sage-hr-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Sage Hr Rate Limits](https://apis.io/rate-limits/sage-hr/sage-hr-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Sage Hr Finops](https://apis.io/finops/sage-hr/sage-hr-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://sage.hr)
- [Documentation](https://apidoc.sage.hr/)
- [Pricing](https://sage.hr/pricing/)
- [Support](https://support.sage.hr/)

## API Evangelist rating

**Kin Score 34.2** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 51.8 |
| Contract quality | 52.4 |
| Contract governance | 9.8 |
| Operational transparency | 10.5 |
| Developer ergonomics | 35.7 |
| Access clarity | 26.3 |

**Agent readiness 24.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 22.5** — Employment & Payroll

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/sage-hr/](https://apis.io/providers/sage-hr/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Sage HR: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/sage-hr/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
