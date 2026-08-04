# Netsmart (netsmart)

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

Netsmart is a healthcare IT platform provider serving behavioral health, post-acute care, and human services organizations. Its CareConnect integration platform exposes FHIR R4 REST APIs for EHR data access, care coordination, analytics, and interoperability across care settings. APIs support Patient Access, System Access (bulk data), Provider Directory, and General Purpose FHIR R4/STU3 resources across Netsmart EHR products including myAvatar, myEvolv, myUnity, GEHRIMED, and TheraOffice.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/netsmart/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/netsmart/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Healthcare IT
- EHR
- FHIR
- Behavioral Health
- Post-Acute Care
- Human Services
- Interoperability
- HL7
- Care Coordination

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Netsmart CareConnect Provider Patient Access API

FHIR R4 API enabling patients and authorized applications to access clinical health records from Netsmart provider EHR systems including myAvatar, myEvolv, myUnity, GEHRIMED, and TheraOffice. Implements SMART on FHIR 2.0 and US Core 6.1.0 profiles.

- **Human URL:** [https://careconnect.netsmartcloud.com/docs/api/fhir/](https://careconnect.netsmartcloud.com/docs/api/fhir/)
- **Base URL:** `https://fhir.netsmartcloud.com/provider/patient-access/v2`

#### Tags

- FHIR R4
- Patient Access
- Provider
- EHR
- Behavioral Health

#### Properties

- [Documentation](https://careconnect.netsmartcloud.com/docs/api/fhir/)
- [Authentication](https://careconnect.netsmartcloud.com/docs/certified/authorization/index.html)
- [Registration](https://careconnect.netsmartcloud.com/docs/getting-started/registration/index.html)

### Netsmart CareConnect Provider System Access API

FHIR R4 backend service API for system-to-system integration and asynchronous bulk data export from Netsmart provider EHR platforms. Supports population-level data extraction per the HL7 Bulk Data 2.0.0 specification. Uses Client Credentials OAuth 2.0 flow.

- **Human URL:** [https://careconnect.netsmartcloud.com/docs/api/fhir/](https://careconnect.netsmartcloud.com/docs/api/fhir/)
- **Base URL:** `https://fhir.netsmartcloud.com/provider/system-access/v2`

#### Tags

- FHIR R4
- System Access
- Bulk Data
- Provider
- Interoperability

#### Properties

- [Documentation](https://careconnect.netsmartcloud.com/docs/api/fhir/)
- [Authentication](https://careconnect.netsmartcloud.com/docs/certified/authorization/index.html)

### Netsmart CareConnect Payer Patient Access API

FHIR R4 API for payer organizations enabling patient-directed access to claims, clinical, and coverage data. Supports 30+ FHIR R4 resources including ExplanationOfBenefit, Coverage, and US Core clinical resources. Implements SMART on FHIR 2.0, US Core 6.1.0, and 21st Century Cures Act compliance requirements.

- **Human URL:** [https://careconnect.netsmartcloud.com/docs/api/fhir/certified/payer/patient-access/index.html](https://careconnect.netsmartcloud.com/docs/api/fhir/certified/payer/patient-access/index.html)
- **Base URL:** `https://fhir.netsmartcloud.com/payer/patient-access/v2`

#### Tags

- FHIR R4
- Patient Access
- Payer
- Claims
- Interoperability

#### Properties

- [Documentation](https://careconnect.netsmartcloud.com/docs/api/fhir/certified/payer/patient-access/index.html)
- [Authentication](https://careconnect.netsmartcloud.com/docs/certified/authorization/index.html)

### Netsmart CareConnect Payer Provider Directory API

Publicly accessible FHIR R4 API for discovering healthcare providers, organizations, locations, services, and insurance plans within payer networks. No authentication required. Implements DaVinci PDex Plan-Net 1.2. Supports 9 searchable FHIR resources with flexible query parameters.

- **Human URL:** [https://careconnect-dev.netsmartdev.com/docs/api/fhir/certified/payer/provider-directory/index.html](https://careconnect-dev.netsmartdev.com/docs/api/fhir/certified/payer/provider-directory/index.html)
- **Base URL:** `https://fhir.netsmartcloud.com/payer/provider-directory/v2`

#### Tags

- FHIR R4
- Provider Directory
- Payer
- Public API
- DaVinci PDex

#### Properties

- [Documentation](https://careconnect-dev.netsmartdev.com/docs/api/fhir/certified/payer/provider-directory/index.html)

### Netsmart CareConnect Service Base URLs API

Public endpoint returning an HL7 FHIR R4 Bundle of Organization and Endpoint resources that describe all available CareConnect service base URLs across Netsmart EHR products. Implements SMART App Launch v2.2.0 User-access Brands specification. No authentication required.

- **Human URL:** [https://careconnect.netsmartcloud.com/docs/certified/service-base-urls/index.html](https://careconnect.netsmartcloud.com/docs/certified/service-base-urls/index.html)
- **Base URL:** `https://fhir.netsmartcloud.com`

#### Tags

- FHIR R4
- Service Discovery
- Public API
- SMART App Launch

#### Properties

- [Documentation](https://careconnect.netsmartcloud.com/docs/certified/service-base-urls/index.html)

## Common Properties

- [Plans](https://raw.githubusercontent.com/api-evangelist/netsmart/refs/heads/main/plans/netsmart-plans-pricing.yml)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/netsmart/refs/heads/main/rate-limits/netsmart-rate-limits.yml)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/netsmart/refs/heads/main/finops/netsmart-finops.yml)
- [Documentation](https://careconnect.netsmartcloud.com/docs/)
- [Portal](https://careconnect.netsmartcloud.com/)
- [Getting Started](https://careconnect.netsmartcloud.com/docs/getting-started/registration/index.html)
- [Authentication](https://careconnect.netsmartcloud.com/docs/certified/authorization/index.html)
- [Sandbox](https://fhirtest.netsmartcloud.com/developers)
- [Portal](https://fhir.netsmartcloud.com/developers)
- [Terms of Service](https://oauthtest.netsmartcloud.com/terms)
- [Terms of Service](https://careconnect.netsmartcloud.com/terms-of-service/index.html)
- [Tutorials](https://careconnect.netsmartcloud.com/docs/tutorials/index.html)
- [Tutorials](https://careconnect-dev.netsmartdev.com/docs/tutorials/testing-fhir-patient-access-apis-with-postman/index.html)
- [Contact](https://www.ntst.com/lp/information-sharing)
- [Website](https://www.ntst.com/)
- [Blog](https://www.ntst.com/blog)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
