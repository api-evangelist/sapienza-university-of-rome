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

Sapienza University of Rome (Sapienza Università di Roma) is Italy's largest university, founded in 1303 and ranked #132 in the QS World University Rankings 2025. This repository catalogs its public developer and API footprint as an [APIs.json](http://apisjson.org) profile. Sapienza operates **no public developer portal, no API gateway and publishes no OpenAPI**, and this profile does not pretend otherwise. What it does operate, on its own `uniroma1.it` hosts, are three verified institution-run machine surfaces — two OAI-PMH 2.0 providers and a Shibboleth SAML 2.0 identity provider — alongside three registry memberships.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/sapienza-university-of-rome/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=sapienza-university-of-rome-api-evangelist&utm_content=repo

## Type

- University / Public Research University — Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Italy, Research, Research Repository, Open Access, Open Data, Library, OAI-PMH, Identity Federation, Scholarly Publishing

## Surfaces

Every surface carries an `x-operator` saying **who runs the thing it describes** — for a university that is almost never the same answer as who the data belongs to.

**Institution-operated**

- **IRIS Research Catalogue OAI-PMH** (`institution`) — OAI-PMH 2.0 provider for Sapienza's institutional research catalogue. `https://iris.uniroma1.it/oai/request` — `verb=Identify` returns 200 with repositoryName "IRIS - UNIROMA1 - prod"; three metadata prefixes (oai_dc, didl, ore). The platform is DSpace-CRIS supplied by CINECA, so no spec is saved here. The DSpace REST API on the same host returns **401 basic-auth**.
- **Riviste Online SApienza (R.O.SA) OAI-PMH** (`institution`) — site-wide OAI-PMH 2.0 provider over 100 open-access journal sets. `https://rosa.uniroma1.it/rosa04/index/oai` — Open Journal Systems 3.3.0.13 (PKP). The OJS REST API v1 on the same host returns **403 `api.403.unauthorized`**.
- **Sapienza Library System Open Data & Linked Data** (`institution`, **dormant**) — a documented 5-star / DCAT-AP_IT dataset catalogue at `sbs.uniroma1.it` whose one dataset download link **404s** and whose linked-data page says in its own words "this website is still under development". Last updated 2017. Recorded honestly rather than credited as a live open-data API.

**Federation**

- **Sapienza Shibboleth Identity Provider** (`federation`) — `https://idp.uniroma1.it/idp/shibboleth`, scope `uniroma1.it`, DisplayName "Sapienza Università di Roma", registered in the IDEM GARR AAI national federation aggregate. A federation is shared by definition and the IdP behind it is the institution's own.

**Registry memberships** (facts about the institution, not contracts it runs)

- **DataCite** (`registry`) — provider `ROMAUNO`, repository `CRUI.UNIROMA1`, prefix 10.13133, 8,051 DOIs resolving to Sapienza hosts.
- **Crossref** (`registry`) — member 13551, prefix 10.53131, 250 DOIs.
- **ROR** (`registry`) — https://ror.org/02be6w209.

## Conformance (Kin Score `education` regime)

Five of the twelve education-regime standards are evidenced from live endpoints: **oai-pmh**, **shibboleth**, **saml**, **datacite**, **crossref**. `orcid`, `scim`, `lti`, `oneroster`, `ed-fi`, `caliper` and `qti` are recorded `conforms: false` with the negative probe that established each.

- Conformance: [conformance/sapienza-university-of-rome-conformance.yml](conformance/sapienza-university-of-rome-conformance.yml)
- Authentication: [authentication/sapienza-university-of-rome-authentication.yml](authentication/sapienza-university-of-rome-authentication.yml)

## Plans / Rate Limits / FinOps

- Plans: [plans/sapienza-university-of-rome-plans-pricing.yml](plans/sapienza-university-of-rome-plans-pricing.yml)
- Rate Limits: [rate-limits/sapienza-university-of-rome-rate-limits.yml](rate-limits/sapienza-university-of-rome-rate-limits.yml)
- FinOps: [finops/sapienza-university-of-rome-finops.yml](finops/sapienza-university-of-rome-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-09-01

## Common Properties

- Website: https://www.uniroma1.it/en
- Research Repository: https://iris.uniroma1.it/
- Identity Federation: https://idp.uniroma1.it/idp/shibboleth
- Open Data: https://sbs.uniroma1.it/data/opendata/
- Library Catalog: https://opac.uniroma1.it/SebinaOpacRMS/.do?sysb=univ
- Course Catalog: https://corsidilaurea.uniroma1.it
- Privacy Policy: https://www.uniroma1.it/it/pagina/piano-privacy-sapienza
- Accessibility: https://www.uniroma1.it/en/pagina/accessibility
- GitHub: https://github.com/Sapienza-University-Rome
- LinkedIn: https://www.linkedin.com/school/sapienza-universita-di-roma/
- Review: [review.yml](review.yml)

## Notes

- Only live-probed or page-confirmed properties are cataloged; **no endpoints were fabricated and no vendor contract is saved under this institution.**
- No Figshare, Elsevier Pure, Ex Libris, Symplectic or Dataverse contract was found or added. The DSpace-CRIS and OJS contracts are product contracts shared by every deployment of that software and belong in the vendors' own repos.
- The `rosa.uniroma1.it` root is a soft-404 catch-all; the live OAI-PMH surface is only reachable under the `/rosa04/` base. Every unknown path under `sbs.uniroma1.it/data/` is likewise a soft-404 returning the same landing page.
- The library OPAC runs vendor Sebina software on an institution host with no public API; the course catalogue is a Drupal 7 site with no data interface.
- There is **no official institutional GitHub organization** — the "Sapienza-University-Rome" org hosts student coursework, not platform code.
- No institutional CKAN, SPARQL, transit, dining, room-booking or HPC allocation API was found.
- The alternate IRIS `oai/openaire4` path did not resolve during probing and was left out as unverified.

## Maintainers

- Kin Lane — kin@apievangelist.com
