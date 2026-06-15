# Sage HR (sage-hr)

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
