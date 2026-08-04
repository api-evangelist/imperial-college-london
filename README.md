# Imperial College London (imperial-college-london)

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

Imperial College London is a UK public research university (QS World 2025 #2) specializing in science, engineering, medicine, and business. Its public developer footprint is infrastructure-oriented rather than a published API program — a large GitHub organization, the Spiral open-access repository, an Ex Libris Primo/Alma library system, and Shibboleth/SAML identity.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/imperial-college-london/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=imperial-college-london-api-evangelist&utm_content=repo)

## Type
- **x-type:** Index (Consumer / 3rd-Party)

## Tags
- Education, Higher Education, University, Research, United Kingdom, Open Access, Repository, Identity

## APIs
- **Spiral Open Access Repository** — DSpace-CRIS repository of 90,000+ research outputs; standard OAI-PMH harvesting and DSpace REST. [Repository](https://spiral.imperial.ac.uk/) · [re3data](https://www.re3data.org/repository/r3d100012406)
- **Imperial Shibboleth IdP (SAML 2.0)** — Federated SSO via the UK Access Management Federation; standards-based, not REST.

## Plans, Rate Limits, FinOps
- [Plans](plans/imperial-college-london-plans-pricing.yml) — Free/open for public endpoints; affiliation/credentialed for the rest.
- [RateLimits](rate-limits/imperial-college-london-rate-limits.yml) — No published global limit; harvest politely.
- [FinOps](finops/imperial-college-london-finops.yml) — Non-commercial; no usage-based API billing.

## Timestamps
- **Created:** 2026-06-03
- **Modified:** 2026-06-03

## Common Properties
- [Website](https://www.imperial.ac.uk/)
- [GitHub](https://github.com/ImperialCollegeLondon)
- [LinkedIn](https://www.linkedin.com/school/imperial-college-london/)

## Notes
- No first-party, self-service developer/API portal (`developer.imperial.ac.uk` / `data.*` open-data portal) was found at the time of profiling.
- Verified live: GitHub org (748 repos). Spiral OAI endpoint was rate-limited (HTTP 429) during probing; endpoint paths are DSpace platform-standard. See [review.yml](review.yml).

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
