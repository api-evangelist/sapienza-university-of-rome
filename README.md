# Sapienza University of Rome (sapienza-university-of-rome)

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
