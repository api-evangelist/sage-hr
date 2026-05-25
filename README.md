# Sage HR (sage-hr)

Sage HR (formerly CakeHR) is a cloud HRIS for small and mid-sized businesses, owned by **Sage Group plc**. It bundles core HR records, leave management, performance, recruitment (ATS), timesheets, shift scheduling, expenses, and onboarding / offboarding into a modular per-employee SaaS. The Sage HR REST API at [apidoc.sage.hr](https://apidoc.sage.hr/) exposes 53 operations across nine resource groups, secured by a tenant-scoped `X-Auth-Token` API key against the customer's own subdomain (`https://{subdomain}.sage.hr/api`).

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/sage-hr/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - HR, HRIS, People, SMB, Leave Management, Recruitment, Performance, Timesheets, Onboarding

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## At a Glance

| Property | Value |
|---|---|
| Vendor | Sage Group plc |
| Product | Sage HR (formerly CakeHR) |
| Segment | SMB HRIS |
| API base | `https://{subdomain}.sage.hr/api` |
| Authentication | API key in `X-Auth-Token` header |
| Documentation | https://apidoc.sage.hr/ |
| OpenAPI source | konfig-sdks/sage-java-sdk (53 ops, 47 paths) |
| Tier | Tier-1 (real OpenAPI available) |

## APIs

### Sage HR Employee API
Manage the employee directory — list active and terminated employees, fetch an employee by ID, create new employees, update employee records and custom fields, retrieve compensation history, and process terminations.

**Human URL:** [https://apidoc.sage.hr/](https://apidoc.sage.hr/)

- [Documentation](https://apidoc.sage.hr/)
- [OpenAPI](openapi/sage-hr-openapi.yml)
- [JSON Schema — Employee](json-schema/sage-hr-employee-schema.json)
- [JSON-LD Context](json-ld/sage-hr-context.jsonld)
- [Naftiko Capability — Employees](capabilities/employees.yaml)

### Sage HR Leave Management API
Manage employee leave — time-off policies, KIT (Keeping In Touch) days, individual allowances and per-employee balances, time-off requests, and out-of-office-today reporting.

- [OpenAPI](openapi/sage-hr-openapi.yml)
- [Naftiko Capability — Leave Management](capabilities/leave-management.yaml)

### Sage HR Recruitment API
Applicant tracking surface — list open positions, fetch position details, list and create applicants (with referral support), pull applicant detail records, and list pipeline actions against an applicant.

- [OpenAPI](openapi/sage-hr-openapi.yml)
- [Naftiko Capability — Recruitment](capabilities/recruitment.yaml)

### Sage HR Performance API
Quarterly performance and goal reporting — overall progress overview, plus drill-down endpoints for company-wide, team, and individual goals.

- [OpenAPI](openapi/sage-hr-openapi.yml)
- [Naftiko Capability — Performance](capabilities/performance.yaml)

### Sage HR Timesheets API
Programmatic clock-in / clock-out for Sage HR Timesheets via `/timesheets/clock-in`.

- [OpenAPI](openapi/sage-hr-openapi.yml)
- [Naftiko Capability — Timesheets](capabilities/timesheets.yaml)

### Sage HR Onboarding and Offboarding API
List task categories and create onboarding and offboarding tasks across an employee lifecycle workflow.

- [OpenAPI](openapi/sage-hr-openapi.yml)
- [Naftiko Capability — Onboarding/Offboarding](capabilities/onboarding-offboarding.yaml)

### Sage HR Documents API
List document categories and upload new employee or company documents (multipart form-data).

- [OpenAPI](openapi/sage-hr-openapi.yml)
- [Naftiko Capability — Documents](capabilities/documents.yaml)

### Sage HR Organization API
Inspect the org structure — list company positions, teams, and termination reasons.

- [OpenAPI](openapi/sage-hr-openapi.yml)
- [Naftiko Capability — Organization](capabilities/organization.yaml)

### Sage HR Vikarina Integrations API
Sage HR -> Vikarina payroll bridge. Transfer job positions, organizational structure, new-starters, contracts, appointments, salaries, bank accounts, terminations, unused vacation days, leave types, timesheets, and bonuses.

- [OpenAPI](openapi/sage-hr-openapi.yml)
- [Naftiko Capability — Vikarina Integrations](capabilities/integrations-vikarina.yaml)

## Modules (Customer-Facing)

| Module | Notes |
|---|---|
| Core HR | Employee directory, org chart, documents (included with subscription) |
| Leave Management | Time-off policies, allowances, requests, KIT days (included with base plan) |
| Performance | Goals (company/team/individual), 1:1s, 360 feedback (add-on) |
| Recruitment | ATS, career site, applicant pipeline (per-position add-on) |
| Shift Scheduling | Shift planning and publication (add-on) |
| Timesheets | Clock-in / clock-out, approvals (add-on) |
| Expenses | Receipts, approvals, reimbursement (add-on) |

## Plans, Rate Limits, FinOps

- [Plans and pricing](plans/sage-hr-plans-pricing.yml) — API Commons Plans 0.1
- [Rate limits](rate-limits/sage-hr-rate-limits.yml) — API Commons Rate Limits 0.1
- [FinOps](finops/sage-hr-finops.yml) — FinOps Framework / FOCUS 1.3 alignment

## Common Resources

- [Sage HR Home](https://sage.hr/)
- [Sage HR on Sage.com](https://www.sage.com/en-gb/sage-business-cloud/hr/)
- [Sage HR API Reference](https://apidoc.sage.hr/)
- [How does Sage HR API work?](https://support.sage.hr/en/articles/3246469-how-does-cakehr-api-work)
- [Sage HR Support](https://support.sage.hr/)
- [Sage HR Pricing](https://sage.hr/pricing/)
- [Sage HR Integrations](https://sage.hr/integrations/)
- [Sage HR on LinkedIn](https://www.linkedin.com/company/sage-hr/)
- [Sage HR on X](https://twitter.com/sagehr)
- [Sage on GitHub](https://github.com/Sage)

## Authentication Quickstart

```bash
curl -H "X-Auth-Token: $SAGE_HR_API_KEY" \
  https://${SAGE_HR_SUBDOMAIN}.sage.hr/api/employees
```

1. Sign in to your Sage HR tenant as an administrator.
2. Open Settings -> Integrations -> API and generate a tenant API key.
3. Use that key as the `X-Auth-Token` request header on every call.
4. Substitute your Sage HR subdomain into the base URL (`https://{subdomain}.sage.hr/api`).

## Notes on Sourcing

- The OpenAPI in `openapi/sage-hr-openapi.yml` is sourced from the konfig-sdks Sage Java SDK ([konfig-sdks/sage-java-sdk](https://github.com/konfig-sdks/sage-java-sdk)), which generates against the public Sage HR API at apidoc.sage.hr. It contains 53 operations across employees, leave management, recruitment, performance, timesheets, documents, onboarding, offboarding, organization, and the Vikarina integration surface.
- Sage's own developer portal (apidoc.sage.hr) is Cloudflare-fronted and not directly machine-fetchable; the canonical reference is the rendered Redoc/Swagger UI at that URL.
- Pricing in `plans/sage-hr-plans-pricing.yml` is indicative; reconcile against current sage.hr/pricing at procurement time.
