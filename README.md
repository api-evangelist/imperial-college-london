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

Imperial College London is a UK public research university and Russell Group member specialising in science, engineering, medicine and business. Re-profiled 2026-08-19 under the API Evangelist **university pipeline**, which settles *who operates* each surface before crediting it. Imperial operates no public developer portal, no open data portal and no self-service API programme. Almost every machine-readable surface running under an `imperial.ac.uk` hostname is a **vendor tenancy** — the DNS proves it.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/imperial-college-london/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=imperial-college-london-api-evangelist&utm_content=repo)

## Type
- **x-type:** university
- **x-category:** Public Research University
- **type:** Index (Consumer / 3rd-Party)

## Tags
- University, Higher Education, Education, Russell Group, United Kingdom, London, Research, Institutional Repository, Open Access, Identity Federation, Learning Management, Library

## Surfaces, by operator

Every entry carries an `x-operator`. `method:` says how we came to hold an artifact; `x-operator` says who runs the thing it describes.

### `institution` — Imperial's own
- **Imperial Shibboleth Identity Provider (SAML 2.0)** — the one unambiguously institution-operated machine-readable contract Imperial publishes. [Metadata](https://shibboleth.imperial.ac.uk/idp/shibboleth) (200, 12.5KB SAML 2.0 EntityDescriptor, entityID `https://shibboleth.imperial.ac.uk/shibboleth`), registered in the [UK Access Management Federation](https://www.ukfederation.org.uk/) aggregate. Host resolves to `shibboleth.gslb21.ic.ac.uk` → `146.179.42.66`, Imperial's own infrastructure — no vendor CNAME.
- **[llms.txt](https://www.imperial.ac.uk/llms.txt)** — 200, 5,803 bytes, self-dated 2026-06-23. Institution-authored agent guidance with per-section crawl priorities and attribution rules.

### `tenant` — Imperial's data, someone else's contract
- **Spiral Open Access Repository (DSpace 7 REST API)** — `spiral.imperial.ac.uk` CNAMEs to `icl-repository.prod.4science.cloud`. DSpace 7.6.1 / DSpace-CRIS 2023.02.05, operated by 4Science. [Repository](https://spiral.imperial.ac.uk/) · [re3data](https://www.re3data.org/repository/r3d100012406)
- **Spiral OAI-PMH endpoint** — [`?verb=Identify`](https://spiral.imperial.ac.uk/server/oai/request?verb=Identify) 200. Eleven metadata prefixes including `etdms` and `uketd_dc`; OpenAIRE CERIF 1.1 compatible. `adminEmail` is `spiral-prd@imperial.ac.uk` and sets are namespaced under Imperial's Handle prefix 10044.
- **Canvas LTI 1.3 / OIDC platform** — `canvas.imperial.ac.uk` → `imperialcollegelondon-vanity.instructure.com`. [JWKS](https://canvas.imperial.ac.uk/api/lti/security/jwks) and [OIDC discovery](https://canvas.imperial.ac.uk/.well-known/openid-configuration) both 200.
- **Blackboard Learn REST API** — `bb.imperial.ac.uk` → `imperialcollege.blackboard.com`. [Version endpoint](https://bb.imperial.ac.uk/learn/api/public/v1/system/version) 200 (Learn 4000.21.0); everything else 401.

Also tenant, no callable surface found: `library-search.imperial.ac.uk` → Ex Libris Primo (`imperial.primo.exlibrisgroup.com`); `profiles.imperial.ac.uk` → Symplectic Elements (`icl.discovery.symplectic.org`, soft-200 SPA shell at every path); `servicemgt.imperial.ac.uk` → ServiceNow.

### `institution`, but gated
- **`api.imperial.ac.uk`** — resolves to `20.77.142.125` (Azure) and answers `/`, `/v1`, `/docs`, `/openapi.json`, `/swagger.json`, `/health` and `/.well-known/openapi.json` with `{"statusCode":404,"message":"Resource not found"}` as `application/json`. A live API gateway with no published surface, not a dead host. Not recorded as an API entry — there is nothing consumable to point at.

## Education-regime standards conformance
[conformance/imperial-college-london-education-standards.yml](conformance/imperial-college-london-education-standards.yml) — probed 2026-08-19 against the Kin Score `education` regime.

| Standard | Status | Operator |
|---|---|---|
| `shibboleth` | confirmed | institution |
| `saml` | confirmed | institution |
| `datacite` | confirmed (provider `URKS`, consortium organisation) | institution |
| `oai-pmh` | confirmed | tenant |
| `lti` | confirmed | tenant |
| `orcid` | unverified — DSpace-CRIS module present, auth-gated | tenant |
| `crossref`, `scim` | not found | — |
| `oneroster`, `ed-fi`, `caliper`, `qti` | not probeable | — |

## Plans, Rate Limits, FinOps
- [Plans](plans/imperial-college-london-plans-pricing.yml) — Free/open for public endpoints; affiliation/credentialed for the rest.
- [RateLimits](rate-limits/imperial-college-london-rate-limits.yml) — No published global limit; harvest politely.
- [FinOps](finops/imperial-college-london-finops.yml) — Non-commercial; no usage-based API billing.

## Timestamps
- **Created:** 2026-06-03
- **Modified:** 2026-08-19

## Common Properties
- [Website](https://www.imperial.ac.uk/) · [llms.txt](https://www.imperial.ac.uk/llms.txt) · [News](https://www.imperial.ac.uk/news/)
- [GitHub organization](https://github.com/ImperialCollegeLondon) (759 public repos) · [LinkedIn](https://www.linkedin.com/school/imperial-college-london/) · [Twitter](https://twitter.com/imperialcollege)
- [Privacy notice](https://www.imperial.ac.uk/about-the-site/privacy/) · [Support (ASK)](https://servicemgt.imperial.ac.uk/ask)
- [Course catalog](https://www.imperial.ac.uk/study/courses/) · [Library discovery](https://library-search.imperial.ac.uk/) · [Research computing](https://www.imperial.ac.uk/computing/people/csg/services/hpc/) · [Generative AI guidance](https://www.imperial.ac.uk/admin-services/library/learning-support/generative-ai-guidance/)

## Notes
- **Three apis[] entries collapsed to one.** `refine-openapis` had split the single Spiral DSpace contract by tag into `core`, `discover` and `root` entries, tripling Imperial's apparent footprint for one vendor-operated API. They are now one entry carrying three OpenAPI pointers.
- No terms-of-service page was found; `/.well-known/security.txt`, `/news/rss/`, `/about/legal/` and `/privacy/` all return 404 HTML.
- `www.imperial.ac.uk/business-school/icbs-apis/` returns 403 but renders a "Page not found" body — a soft-404, and `robots.txt` disallows the path. Not a surface.
- The cohort audit script grades by registrable domain alone, so it reads all eight of these as `institution`. The `x-operator` labels here are DNS-verified and disagree with it on five of them.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
