# Imperial College London (imperial-college-london)

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
