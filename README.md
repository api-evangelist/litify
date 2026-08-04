# Litify (litify)

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

Litify is a legal operating system built on Salesforce that provides REST APIs for managing matters, intakes, documents, tasks, time tracking, billing, and client communications for law firms and legal departments. Integrators access Litify functionality via the Salesforce REST API and the Litify Docrio API under the terms of the Litify API Integration Agreement.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/litify/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/litify/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Legal
- Law Firms
- Matter Management
- Intake Management
- Document Management
- Time Tracking
- Billing
- Client Communications
- Legal Technology
- Salesforce

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Litify Salesforce REST API

Provides access to the Litify legal operating system via the Salesforce REST API. Supports managing matters, intakes, documents, tasks, time tracking, billing, and client communications for law firms. Authentication uses an approved integrator key token provided by Litify alongside Salesforce OAuth 2.0.

- **Human URL:** [https://www.litify.com/platform](https://www.litify.com/platform)
- **Base URL:** `https://login.salesforce.com`

#### Tags

- Matters
- Intakes
- Documents
- Tasks
- Time Tracking
- Billing
- Client Communications

#### Properties

- [Documentation](https://www.litify.com/platform)
- [Legal Terms Of Service](https://www.litify.com/legal/litify-api-integration-agreement)
- [Integrations](https://www.litify.com/platform)

### Litify Docrio API

Provides access to Litify's Docrio document management layer, enabling integrators to create, retrieve, and manage documents and folders associated with legal matters. Documents uploaded via integrations are stored in Docrio and linked to matter records.

- **Human URL:** [https://www.litify.com/blog/docs-made-delightful](https://www.litify.com/blog/docs-made-delightful)
- **Base URL:** `https://login.salesforce.com`

#### Tags

- Documents
- Document Management
- File Storage
- Matters

#### Properties

- [Documentation](https://www.litify.com/blog/docs-made-delightful)
- [Legal Terms Of Service](https://www.litify.com/legal/litify-api-integration-agreement)

## Common Properties

- [Plans](https://raw.githubusercontent.com/api-evangelist/litify/refs/heads/main/plans/litify-plans-pricing.yml)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/litify/refs/heads/main/rate-limits/litify-rate-limits.yml)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/litify/refs/heads/main/finops/litify-finops.yml)
- [Website](https://www.litify.com/)
- [Blog](https://www.litify.com/blog)
- [Legal Terms Of Service](https://www.litify.com/legal/litify-api-integration-agreement)
- [Integrations](https://slashdot.org/software/p/Litify/integrations/)
- [Pricing](https://www.litify.com/pricing)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
