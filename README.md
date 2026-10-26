# Workday Reporting (workday-reporting)

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

APIs for accessing Workday reporting functionality including custom reports, report data extraction, and report management.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/workday-reporting/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/workday-reporting/refs/heads/main/apis.yml)

## Tags

- Analytics
- Business Intelligence
- Financial Reporting
- Hr Data
- Reporting

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Workday Report as a Service (RaaS)

REST API for retrieving report data from custom reports in Workday.

- **Human URL:** [https://community.workday.com/sites/default/files/file-hosting/productionapi/Reporting/v1/index.html](https://community.workday.com/sites/default/files/file-hosting/productionapi/Reporting/v1/index.html)
- **Base URL:** `https://wd2-impl-services1.workday.com/ccx/service/{tenant}/Reporting`

#### Tags

- Data Extraction
- Raas
- Reports
- Rest

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/Reporting/v1/index.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/productionapi/Reporting/v1/Reporting.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://doc.workday.com/admin-guide/en-us/lef1569276711011/kqh1569276711095.html)
- [Client  Libraries](https://github.com/Workday/raas-python)
- [Postman Collection](collections/workday-reporting-raas.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-reporting-raas.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workday Custom Reports API

API for managing and executing custom reports programmatically.

- **Human URL:** [https://doc.workday.com/reader/J1YvI9CYZUWl1U7_PSHyHA/sxVLLu9fFSJM5BffiOZwmA](https://doc.workday.com/reader/J1YvI9CYZUWl1U7_PSHyHA/sxVLLu9fFSJM5BffiOZwmA)
- **Base URL:** `https://wd2-impl-services1.workday.com/ccx/service/{tenant}`

#### Tags

- Custom Reports
- Report Execution
- Soap

#### Properties

- [Documentation](https://doc.workday.com/reader/J1YvI9CYZUWl1U7_PSHyHA/sxVLLu9fFSJM5BffiOZwmA)
- [W S D L](https://community.workday.com/sites/default/files/file-hosting/productionapi/Report_as_a_Service/Report_as_a_Service.html)
- [Authentication](https://doc.workday.com/admin-guide/en-us/lef1569276711011/kqh1569276711095.html)
- [Postman Collection](collections/workday-reporting-raas.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-reporting-raas.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workday Advanced Reports API

API for accessing advanced reporting features including matrix reports and composite reports.

- **Human URL:** [https://doc.workday.com/reader/wsiU0cn5CkB~MbuzChYv1w/_YO8X6WAWjLFBkBLamVxkw](https://doc.workday.com/reader/wsiU0cn5CkB~MbuzChYv1w/_YO8X6WAWjLFBkBLamVxkw)
- **Base URL:** `https://wd2-impl-services1.workday.com/ccx/service/{tenant}`

#### Tags

- Advanced Reporting
- Composite Reports
- Matrix Reports

#### Properties

- [Documentation](https://doc.workday.com/reader/wsiU0cn5CkB~MbuzChYv1w/_YO8X6WAWjLFBkBLamVxkw)
- [Guides](https://doc.workday.com/reader/wsiU0cn5CkB~MbuzChYv1w/root_landing.html)
- [Postman Collection](collections/workday-reporting-raas.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-reporting-raas.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workday Prism Analytics REST API

REST API for working with Workday Prism Analytics tables, data change tasks, and datasets. Enables programmatic creation and management of analytics data including ingesting external data, building transformation pipelines, and publishing datasets for reporting and analysis.

- **Human URL:** [https://doc.workday.com/admin-guide/en-us/workday-prism-analytics/workday-prism-analytics-api.html](https://doc.workday.com/admin-guide/en-us/workday-prism-analytics/workday-prism-analytics-api.html)
- **Base URL:** `https://wd2-impl-services1.workday.com/ccx/api/prismAnalytics/v2/{tenant}`

#### Tags

- Analytics
- Data Integration
- Datasets
- Prism Analytics

#### Properties

- [Documentation](https://doc.workday.com/admin-guide/en-us/workday-prism-analytics/workday-prism-analytics-api.html)
- [Authentication](https://doc.workday.com/admin-guide/en-us/lef1569276711011/kqh1569276711095.html)
- [Client  Libraries](https://github.com/Workday/prism-python)
- [Postman Collection](collections/workday-reporting-raas.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-reporting-raas.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workday Prism Analytics SOAP Web Service

SOAP web service for creating, editing, and retrieving objects related to Prism Analytics, including analytic dimension business objects, analytic dimension hierarchies, and analytic dimension values.

- **Human URL:** [https://community.workday.com/sites/default/files/file-hosting/productionapi/Prism_Analytics/v45.2/Prism_Analytics.html](https://community.workday.com/sites/default/files/file-hosting/productionapi/Prism_Analytics/v45.2/Prism_Analytics.html)
- **Base URL:** `https://wd2-impl-services1.workday.com/ccx/service/{tenant}/Prism_Analytics`

#### Tags

- Analytic Dimensions
- Hierarchies
- Prism Analytics
- SOAP

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/Prism_Analytics/v45.2/Prism_Analytics.html)
- [W S D L](https://community.workday.com/sites/default/files/file-hosting/productionapi/Prism_Analytics/v45.2/Prism_Analytics.wsdl)
- [Postman Collection](collections/workday-reporting-raas.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-reporting-raas.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workday WQL API

Workday Query Language (WQL) API enabling SQL-like querying of Workday data through REST endpoints. Provides high-performance data access for reporting and analytics use cases, with support for pagination, filtering, sorting, and aggregation controlled via OAuth 2.0 tokens.

- **Human URL:** [https://doc.workday.com/admin-guide/en-us/reporting-and-analytics/custom-reports-and-analytics/workday-query-language-wql-/aht1611188422513.html](https://doc.workday.com/admin-guide/en-us/reporting-and-analytics/custom-reports-and-analytics/workday-query-language-wql-/aht1611188422513.html)
- **Base URL:** `https://wd2-impl-services1.workday.com/ccx/api/wql/v1/{tenant}`

#### Tags

- Analytics
- Data Access
- Query Language
- Reporting

#### Properties

- [Documentation](https://doc.workday.com/admin-guide/en-us/reporting-and-analytics/custom-reports-and-analytics/workday-query-language-wql-/aht1611188422513.html)
- [Authentication](https://doc.workday.com/admin-guide/en-us/lef1569276711011/kqh1569276711095.html)
- [Postman Collection](collections/workday-reporting-raas.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-reporting-raas.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Developer  Portal](https://developer.workday.com)
- [Community](https://community.workday.com)
- [Getting Started](https://community.workday.com/api-start)
- [Documentation](https://community.workday.com/api)
- [Authentication](https://doc.workday.com/admin-guide/en-us/lef1569276711011/kqh1569276711095.html)
- [Rate Limits](https://doc.workday.com/reader/J1YvI9CYZUWl1U7_PSHyHA/f8K9WJ7Kh5FfQDNnvlHNFQ)
- [Status Page](https://community.workday.com/trust/status)
- [Support](https://www.workday.com/en-us/customer-experience/support.html)
- [Terms of Service](https://www.workday.com/en-us/legal.html)
- [Privacy Policy](https://www.workday.com/en-us/privacy.html)
- [Blog](https://blog.workday.com/en-us/application-development.html)
- [Website](https://www.workday.com)
- [Sign Up](https://resourcecenter.workday.com/)
- [GitHub Organization](https://github.com/Workday)
- [Reference](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [Marketplace](https://marketplace.workday.com/en-US/home)
- [Partners](https://www.workday.com/en-us/company/partners/overview.html)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
