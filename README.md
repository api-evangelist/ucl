# UCL (ucl)

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

University College London (UCL) is a public research university in London, United Kingdom, and a member of the Russell Group. This profile is a re-assessment: UCL's flagship developer surface, **UCL API** (uclapi.com) — a student-built, ISD-backed, open-source, OAuth2-secured platform exposing room bookings, timetables, staff search, desktop and study-space availability and workspaces — was genuinely UCL's own engineering, and **as of 2026-08-19 the entire estate is retired**: uclapi.com, api.uclapi.com, docs.uclapi.com and status.uclapi.com all fail to complete a TCP connection on port 80 or 443. What remains is almost entirely bought rather than built. Every surface below carries an `x-operator` recording who actually runs it.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ucl/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ucl-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Category

- Public Research University (`x-type: university`)

## Tags

Education, Higher Education, University, United Kingdom, London, Russell Group, Research, Open Access, Research Data, Research Repository, Library, Identity Federation, Research Computing, Course Catalog

## Surfaces

Operator attribution is settled before any contract is saved. `institution` means UCL runs the thing; `tenant` means the data is UCL's but a vendor wrote and runs the contract.

| Surface | Operator | Vendor | Probe |
|---|---|---|---|
| [UCL Discovery — OAI-PMH](https://discovery.ucl.ac.uk/) | `institution` | — | 403 |
| [UCL Research Data Repository (Figshare tenancy)](https://rdr.ucl.ac.uk/) | `tenant` | Figshare | 202 |
| [UCL Profiles / IRIS (Symplectic Elements tenancy)](https://profiles.ucl.ac.uk/) | `tenant` | Symplectic (Digital Science) | 200 |
| [UCL Library Discovery (Ex Libris Primo VE tenancy)](https://ucl.primo.exlibrisgroup.com/discovery/search?vid=44UCL_INST:UCL_VU2) | `tenant` | Ex Libris (Clarivate) | 200 |
| [UCL site search (Funnelback tenancy)](https://search2.ucl.ac.uk/) | `tenant` | Funnelback (Squiz) | 200 |
| [UCL Identity Provider — UK Access Management Federation](https://www.ukfederation.org.uk/) | `tenant` | OpenAthens (Jisc / EBSCO) | 200 |

No vendor contract is saved under this institution. In particular the Figshare contract that 25 universities in this catalog were previously credited with authoring is **not** stored here — the UCL Research Data Repository is recorded as a Figshare tenancy instead (rdr.ucl.ac.uk CNAMEs to figshare.com; UCL's holdings are addressed as `institution=549` on Figshare's shared host).

## Retired

UCL API's 7 OpenAPIs, 14 Postman/OpenCollection files, agent-access contract and every schema, example, rule, vocabulary and scope derived from them were removed. The source repositories stay public and are kept as pointers:

- https://github.com/uclapi/uclapi — live, last pushed 2026-05-06, not archived
- https://github.com/uclapi/uclapi-openapi — **archived** since 2021

One further UCL-authored OpenAPI exists (github.com/UCL/isenseflu-openapi, © 2019 UCL, GPL-3.0) but it declares no `servers[]` and every candidate deployment host is dead, so it was not registered as a surface.

## Domain standards (education regime)

See [conformance/ucl-education-standards-conformance.yml](conformance/ucl-education-standards-conformance.yml). Evidenced: **oai-pmh** (UCL Discovery, institution-operated, confirmed via re3data r3d100012417), **shibboleth** and **saml** (UCL IdP registered in the UK Access Management Federation since 2009, entityID `https://shib-idp.ucl.ac.uk/shibboleth`, scope `ucl.ac.uk` — note the SSO endpoints resolve to OpenAthens, not to UCL), and **datacite** (UCL's own client BL.UCLD, DOI prefix 10.5522). Not evidenced and not claimed: scim, lti, oneroster, ed-fi, caliper, qti, orcid, crossref.

## Coverage

State: **covered** — `no_institution_operated_api`

UCL publishes no institution-operated, publicly callable API. Its one genuinely institution-operated machine-readable surface is the UCL Discovery OAI-PMH endpoint, which is live but sits behind a Cloudflare challenge (403) and could not be read unattended. Every other surface found is a vendor tenancy: Figshare, Symplectic, Ex Libris, Funnelback and OpenAthens. UCL API (uclapi.com), which WAS UCL's own engineering and the strongest university developer surface in this catalog, is fully retired — no TCP connection completes on uclapi.com, api.uclapi.com, docs.uclapi.com or status.uclapi.com. Its 12 contracts and every artifact derived from them were removed; the source repositories are kept as pointers. One further UCL-authored OpenAPI exists (github.com/UCL/isenseflu-openapi, '(c) 2019 UCL', GPL-3.0) but it declares no servers[] and every candidate deployment host is dead, so it was NOT registered as a surface. This is a correct thin profile: the absence is the finding, and the score should fall accordingly.

## Plans

See [plans/ucl-plans-pricing.yml](plans/ucl-plans-pricing.yml). UCL is non-commercial; no API is sold.

## Rate Limits

See [rate-limits/ucl-rate-limits.yml](rate-limits/ucl-rate-limits.yml).

## FinOps

See [finops/ucl-finops.yml](finops/ucl-finops.yml).

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-19

## Common Properties

- Website: https://www.ucl.ac.uk/
- GitHubOrganization: https://github.com/UCL
- GitHub: https://github.com/uclapi
- SourceCode: https://github.com/uclapi/uclapi
- License (MIT): https://github.com/uclapi/uclapi/blob/master/LICENSE
- ResearchRepository (UCL Discovery (open access, institution-operated)): https://discovery.ucl.ac.uk/
- ResearchRepository (UCL Research Data Repository (Figshare tenancy)): https://rdr.ucl.ac.uk/
- LibraryCatalog (UCL Library Discovery (Ex Libris Primo VE tenancy)): https://ucl.primo.exlibrisgroup.com/discovery/search?vid=44UCL_INST:UCL_VU2
- CourseCatalog (UCL Module Catalogue): https://www.ucl.ac.uk/module-catalogue/
- IdentityFederation (UK Access Management Federation metadata (entityID https://shib-idp.ucl.ac.uk/shibboleth)): http://metadata.ukfederation.org.uk/ukfederation-metadata.xml
- ResearchComputing (UCL Research Computing documentation (Myriad, Kathleen)): https://www.rc.ucl.ac.uk/docs/
- ResearchComputing (UCL Centre for Advanced Research Computing): https://www.ucl.ac.uk/advanced-research-computing
- AIPolicy (UCL Generative AI Hub): https://www.ucl.ac.uk/teaching-learning/generative-ai-hub
- Support: https://www.ucl.ac.uk/isd/
- Documentation: https://www.ucl.ac.uk/library/open-science-research-support/research-data-management
- PrivacyPolicy: https://www.ucl.ac.uk/legal-services/privacy
- DataProtection: https://www.ucl.ac.uk/data-protection/
- Blog: https://medium.com/feed/ucl-api
- LinkedIn: https://uk.linkedin.com/company/uclapi
- Conformance: conformance/ucl-education-standards-conformance.yml
- DomainSecurity: security/ucl-domain-security.yml
- Plans: plans/ucl-plans-pricing.yml
- RateLimits: rate-limits/ucl-rate-limits.yml
- FinOps: finops/ucl-finops.yml
- Review: review.yml

## Notes

All entries reflect publicly verifiable sources only; no endpoints or credentials were invented. Every pointer in this repository was fetched on 2026-08-19 and returned HTTP 200. Two live surfaces answer with a bot challenge rather than content and are graded live, not dead: discovery.ucl.ac.uk returns a Cloudflare interstitial (403) and rdr.ucl.ac.uk returns an AWS WAF challenge (202). This is a correct thin profile — UCL publishes no institution-operated, publicly callable API, and the absence is the finding.

## Maintainers

- Kin Lane — kin@apievangelist.com
