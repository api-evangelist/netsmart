# Netsmart (netsmart)

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
