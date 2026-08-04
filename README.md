# Sapienza University of Rome (sapienza-university-of-rome)

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

Sapienza University of Rome (Sapienza Università di Roma) is Italy's largest university, ranked #132 in the QS World University Rankings 2025. This repository catalogs its public developer and API footprint as an [APIs.json](http://apisjson.org) profile. Sapienza does not operate a single unified public developer portal; its verified machine-readable surface is centered on research and library data — the IRIS DSpace research catalogue (OAI-PMH) and the Sapienza Library System open/linked data publishing.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/sapienza-university-of-rome/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=sapienza-university-of-rome-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Data, Library, OAI-PMH, Italy

## APIs

- **IRIS Research Catalogue OAI-PMH** — OAI-PMH 2.0 metadata harvesting for Sapienza's institutional research repository (DSpace/CINECA). Base URL `https://iris.uniroma1.it/oai/request`. Docs: https://www.uniroma1.it/en/pagina/iris-support
- **Sapienza Library System Open Data & Linked Data** — Library and digital-resource open data (CC BY 4.0, 5-star / DCAT-AP_IT) and linked data. Docs: https://sbs.uniroma1.it/data/opendata/

## Plans / Rate Limits / FinOps

- Plans: [plans/sapienza-university-of-rome-plans-pricing.yml](plans/sapienza-university-of-rome-plans-pricing.yml)
- Rate Limits: [rate-limits/sapienza-university-of-rome-rate-limits.yml](rate-limits/sapienza-university-of-rome-rate-limits.yml)
- FinOps: [finops/sapienza-university-of-rome-finops.yml](finops/sapienza-university-of-rome-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.uniroma1.it/en
- GitHub: https://github.com/Sapienza-University-Rome
- LinkedIn: https://www.linkedin.com/school/sapienza-universita-di-roma/
- Review: [review.yml](review.yml)

## Notes

- Only live-probed or page-confirmed properties are cataloged; no endpoints were fabricated.
- The IRIS OAI-PMH `request` endpoint was verified live returning valid OAI-PMH 2.0 XML.
- The alternate IRIS `oai/openaire4` path did not resolve during probing and was left out as unverified.
- The "Sapienza-University-Rome" GitHub org hosts research/coursework projects, not official platform APIs.
- Identity is federated via the Italian IDEM Shibboleth/SAML federation; no public API docs are exposed.

## Maintainers

- Kin Lane — kin@apievangelist.com
