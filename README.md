# Administrative Office of the U.S. Courts (administrative-office-of-the-u-s-courts)

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
