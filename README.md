# Administrative Office of the U.S. Courts (administrative-office-of-the-u-s-courts)
The Administrative Office of the United States Courts is the administrative agency of the United States federal court system, established in 1939. It provides legislative, administrative, legal, financial, management, program, and information technology support services to the federal courts. The agency operates PACER (Public Access to Court Electronic Records), which provides programmatic access to case and docket information from Federal Appellate, District, and Bankruptcy courts via the PACER Authentication API and PACER Case Locator (PCL) REST API. The agency also provides CM/ECF developer resources for building tools that interface with the Case Management and Electronic Case Filing system.

**URL:** [https://www.uscourts.gov/](https://www.uscourts.gov/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Courts, Federal Government, Legal, PACER, Case Records, Judiciary, Open Data

## Timestamps

- **Created:** 2024-11-20
- **Modified:** 2026-04-19

## APIs

### PACER Authentication API
The PACER Authentication API allows users to authenticate automatically and without a user interface, facilitating programmatic access for automated systems to court records. Users provide PACER credentials to receive an authentication token used to access the PCL API and other PACER services. Required before using the PACER Case Locator API.

**Human URL:** [https://pacer.uscourts.gov/help/pacer/pacer-authentication-api-user-guide](https://pacer.uscourts.gov/help/pacer/pacer-authentication-api-user-guide)

#### Tags:

 - Authentication, Courts, PACER, REST API

#### Properties

- [Documentation](https://pacer.uscourts.gov/help/pacer/pacer-authentication-api-user-guide)
- [APIReference](https://pacer.uscourts.gov/help/pacer/pacer-authentication-api-user-guide)
- [OpenAPI](openapi/pacer-authentication-api-openapi.yml)

### PACER Case Locator (PCL) API
The PACER Case Locator (PCL) API is a REST API providing programmatic access to a nationwide index of federal court cases across all Federal Appellate, District, and Bankruptcy courts. Supports both immediate searches (returning up to 5,400 items per search) and batch searches (up to 108,000 items). Case searches return groups of cases; party searches return parties associated with cases. Supports JSON and XML encoding. Requires PACER authentication token. Separate QA and Production environments are available for development and testing.

**Human URL:** [https://pacer.uscourts.gov/help/pacer/pacer-case-locator-pcl-api-user-guide](https://pacer.uscourts.gov/help/pacer/pacer-case-locator-pcl-api-user-guide)

#### Tags:

 - Courts, Legal, Case Records, Federal Courts, REST API, PACER

#### Properties

- [Documentation](https://pacer.uscourts.gov/help/pacer/pacer-case-locator-pcl-api-user-guide)
- [APIReference](https://pacer.uscourts.gov/sites/default/files/files/PCL-API-Document_3.pdf)
- [GettingStarted](https://pacer.uscourts.gov/file-case/developer-resources)
- [OpenAPI](openapi/pacer-case-locator-pcl-api-openapi.yml)

## Common Properties

- [Website](https://www.uscourts.gov/)
- [Portal](https://pacer.uscourts.gov/)
- [DeveloperPortal](https://pacer.uscourts.gov/file-case/developer-resources)
- [SignUp](https://pacer.uscourts.gov/register-account)
- [Contact](https://pacer.uscourts.gov/contact-us)

## Features

| Name | Description |
|------|-------------|
| Federal Court Case Search | Programmatic search across a nationwide index of all Federal Appellate, District, and Bankruptcy court cases using the PCL REST API, supporting case search and party search with immediate and batch result modes. |
| Automated PACER Authentication | Token-based authentication API enabling automated systems to obtain PACER authentication tokens without requiring a user interface, suitable for integration into automated data pipelines and legal research tools. |
| CM/ECF Developer Integration | Technical resources for developers building tools that interface with the Case Management and Electronic Case Filing (CM/ECF) system, including XML tag specifications, NextGen CM/ECF documentation, and release notes for appellate and bankruptcy systems. |
| Court Lookup Data Feeds | JSON and XML data feeds providing court lookup information for identifying CM/ECF courts and their configurations, available for integration into court filing software. |
| Bankruptcy Filing Integration | Specialized resources for bankruptcy petition preparation software and case trustee management software vendors, including creditor claim filing specifications and official form changes. |
| Bulk Data Access | Commercial users can run large batch data pulls via the PCL API, with recommended off-peak hours (6 p.m. to 6 a.m. Central Time) to minimize system impact. |

## Use Cases

| Name | Description |
|------|-------------|
| Legal Research Automation | Law firms and legal research platforms can use the PCL API to programmatically search federal court case indexes and retrieve case and party information for automated legal research workflows. |
| Litigation Monitoring | Corporate legal departments can monitor federal court filings involving specific parties, cases, or subject matters using automated PCL API queries. |
| Bankruptcy Software Integration | Bankruptcy petition preparation software and trustee management applications can integrate with CM/ECF and PACER APIs to file documents, retrieve case data, and manage creditor information. |
| Court Data Analytics | Academic researchers and legal analytics firms can build datasets of federal court case activity using batch PCL API searches across federal court jurisdictions. |
| Legal Technology Development | Legal technology companies can build PACER-integrated products for case tracking, docket monitoring, and court record retrieval using the PACER Authentication and PCL APIs. |

## Integrations

| Name | Description |
|------|-------------|
| CM/ECF System | Case Management and Electronic Case Filing system for all federal courts. |
| PACER Case Locator | Nationwide index of federal court cases searchable via REST API. |
| NextGen CM/ECF | Next-generation electronic filing system with enhanced developer integration support. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [PACER Authentication API](openapi/pacer-authentication-api-openapi.yml)
- [PACER Case Locator (PCL) API](openapi/pacer-case-locator-pcl-api-openapi.yml)

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
