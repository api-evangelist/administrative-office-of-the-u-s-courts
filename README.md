# Administrative Office of the U.S. Courts (administrative-office-of-the-u-s-courts)

The Administrative Office of the United States Courts is the administrative agency of the United States federal court system, established in 1939. It provides legislative, administrative, legal, financial, management, program, and information technology support services to the federal courts. The agency operates PACER (Public Access to Court Electronic Records), which provides programmatic access to case and docket information from Federal Appellate, District, and Bankruptcy courts via the PACER Authentication API and PACER Case Locator (PCL) REST API. The agency also provides CM/ECF developer resources for building tools that interface with the Case Management and Electronic Case Filing system.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/administrative-office-of-the-u-s-courts/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/administrative-office-of-the-u-s-courts/refs/heads/main/apis.yml)

## Tags

- Courts
- Federal Government
- Legal
- PACER
- Case Records
- Judiciary
- Open Data

## Timestamps

- **Created:** 2024-11-20
- **Modified:** 2026-05-19

## APIs

### PACER Authentication API

The PACER Authentication API allows users to authenticate automatically and without a user interface, facilitating programmatic access for automated systems to court records. Users provide PACER credentials to receive an authentication token used to access the PCL API and other PACER services. Required before using the PACER Case Locator API.

- **Human URL:** [https://pacer.uscourts.gov/help/pacer/pacer-authentication-api-user-guide](https://pacer.uscourts.gov/help/pacer/pacer-authentication-api-user-guide)

#### Tags

- Authentication
- Courts
- PACER
- REST API

#### Properties

- [Documentation](https://pacer.uscourts.gov/help/pacer/pacer-authentication-api-user-guide)
- [API Reference](https://pacer.uscourts.gov/help/pacer/pacer-authentication-api-user-guide)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/administrative-office-of-the-u-s-courts/refs/heads/main/openapi/pacer-authentication-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pacer-authentication-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pacer-authentication-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/pacer-case-locator-pcl-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pacer-case-locator-pcl-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PACER Case Locator (PCL) API

The PACER Case Locator (PCL) API is a REST API providing programmatic access to a nationwide index of federal court cases across all Federal Appellate, District, and Bankruptcy courts. Supports both immediate searches (returning up to 5,400 items per search) and batch searches (up to 108,000 items). Case searches return groups of cases; party searches return parties associated with cases. Supports JSON and XML encoding. Requires PACER authentication token. Separate QA and Production environments are available for development and testing.

- **Human URL:** [https://pacer.uscourts.gov/help/pacer/pacer-case-locator-pcl-api-user-guide](https://pacer.uscourts.gov/help/pacer/pacer-case-locator-pcl-api-user-guide)

#### Tags

- Courts
- Legal
- Case Records
- Federal Courts
- REST API
- PACER

#### Properties

- [Documentation](https://pacer.uscourts.gov/help/pacer/pacer-case-locator-pcl-api-user-guide)
- [API Reference](https://pacer.uscourts.gov/sites/default/files/files/PCL-API-Document_3.pdf)
- [Getting Started](https://pacer.uscourts.gov/file-case/developer-resources)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/administrative-office-of-the-u-s-courts/refs/heads/main/openapi/pacer-case-locator-pcl-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pacer-authentication-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pacer-authentication-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/pacer-case-locator-pcl-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pacer-case-locator-pcl-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/administrative-office-of-the-united-states-courts)
- [Website](https://www.uscourts.gov/)
- [Portal](https://pacer.uscourts.gov/)
- [Developer Portal](https://pacer.uscourts.gov/file-case/developer-resources)
- [Sign Up](https://pacer.uscourts.gov/register-account)
- [Contact](https://pacer.uscourts.gov/contact-us)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
