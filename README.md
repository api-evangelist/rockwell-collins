# Rockwell Collins (rockwell-collins)

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

Rockwell Collins was a major American company providing avionics and information technology systems and services to government agencies and aircraft manufacturers. In 2018, Rockwell Collins was acquired by United Technologies and became part of Collins Aerospace, a subsidiary of RTX Corporation (formerly Raytheon Technologies). Collins Aerospace provides flight deck systems, cabin electronics, mission systems, communications, and advanced data services including FlightAware AeroAPI for aviation data. The Collins Digital Exchange offers API products for aerospace and defense integration.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rockwell-collins/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rockwell-collins/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Avionics
- Aerospace
- Defense
- Aviation
- Flight Deck

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-19

## APIs

### FlightAware AeroAPI

FlightAware AeroAPI (formerly FlightXML) is a RESTful aviation data API acquired by Collins Aerospace in 2021. It provides access to real-time and historical flight tracking data, airport activity, flight positions, predictive ETAs powered by machine learning (FlightAware Foresight), and configurable alerting on flight events. With over 60 distinct endpoints organized into 7 functional families, AeroAPI supports aviation operations, maintenance scheduling, flight planning, and resource management.

- **Human URL:** [https://www.flightaware.com/commercial/aeroapi/](https://www.flightaware.com/commercial/aeroapi/)
- **Base URL:** `https://aeroapi.flightaware.com/aeroapi`

#### Tags

- Aviation
- Flight Tracking
- Aerospace
- REST
- Real-Time Data

#### Properties

- [Documentation](https://www.flightaware.com/commercial/aeroapi/)
- [Portal](https://www.flightaware.com/aeroapi/portal)
- [OpenAPI](openapi/flightaware-aeroapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flightaware-aeroapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flightaware-aeroapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub Repository](https://github.com/flightaware/aeroapps)

### Collins Digital Exchange APIs

The Collins Digital Exchange is a developer portal operated by Collins Aerospace providing API products for aerospace integration. The portal provides quick-start guides and authenticated access to Collins Aerospace API products for authorized partners, customers, and suppliers.

- **Human URL:** [https://developer.collins.com/api-products](https://developer.collins.com/api-products)
- **Base URL:** `https://developer.collins.com`

#### Tags

- Aerospace
- Defense
- Integration
- Partner APIs

#### Properties

- [Portal](https://developer.collins.com/api-products)
- [Postman Collection](collections/flightaware-aeroapi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flightaware-aeroapi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/rockwell-collins)
- [Website](https://www.rockwellcollins.com)
- [Website](https://www.rtx.com/collinsaerospace/)
- [Portal](https://developer.collins.com/api-products)
- [Portal](https://portal.rockwellcollins.com/)
- [Portal](https://customers.collinsaerospace.com/)
- [Documentation](https://www.flightaware.com/commercial/aeroapi/)
- [Support](https://www.rtx.com/collinsaerospace/what-we-do/service-and-support/support/support-lookup)
- [OpenAPI](openapi/flightaware-aeroapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/rockwell-collins-flight-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/rockwell-collins-flight-structure.json)
- [J S O N L D Context](json-ld/rockwell-collins-context.jsonld)
- [Vocabulary](vocabulary/rockwell-collins-vocabulary.yml)
- [Spectral Ruleset](rules/rockwell-collins-rules.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
