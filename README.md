# Workday Reporting (workday-reporting)

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
