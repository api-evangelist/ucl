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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

University College London (UCL) is a public research university in London, United Kingdom, ranked #9 in the QS World University Rankings 2025. UCL stands out among universities for a genuinely mature, public developer footprint: **UCL API** (uclapi.com) is an open-source, OAuth2-secured platform — student-built and backed by UCL's Information Services Division (ISD) — that exposes UCL digital services such as room bookings, timetables, staff search, desktop and study-space availability, and workspaces. UCL also runs open-research infrastructure including UCL Discovery and the Figshare-powered UCL Research Data Repository.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ucl/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ucl-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, United Kingdom, Open Data, Research, Library, Timetable

## APIs

- **UCL API Room Bookings** — room bookings and free/empty rooms across UCL. [Docs](https://uclapi.com/docs)
- **UCL API Timetable** — personal and module timetables with filters. [Docs](https://uclapi.com/docs)
- **UCL API Search** — staff/people directory search. [Docs](https://uclapi.com/docs)
- **UCL API Workspaces** — library study-space availability, sensors, and maps. [Docs](https://uclapi.com/docs)
- **UCL API Resources** — desktop/computer availability across UCL. [Docs](https://uclapi.com/docs)
- **UCL API OAuth** — OAuth2 authentication/authorisation via the UCL login system. [Docs](https://uclapi.com/docs)
- **UCL Discovery (OAI-PMH)** — open-access repository metadata harvesting (EPrints; OAI endpoint protected at review). [Site](https://discovery.ucl.ac.uk/)
- **UCL Research Data Repository** — Figshare-powered institutional data repository with DOIs. [Site](https://rdr.ucl.ac.uk/)

Public OpenAPI definition: https://github.com/uclapi/uclapi-openapi

## Plans

See [plans/ucl-plans-pricing.yml](plans/ucl-plans-pricing.yml). UCL API is free to use; access requires UCL affiliation.

## Rate Limits

See [rate-limits/ucl-rate-limits.yml](rate-limits/ucl-rate-limits.yml). UCL API documents a quota of 10,000 requests/day, resetting at midnight London time.

## FinOps

See [finops/ucl-finops.yml](finops/ucl-finops.yml).

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.ucl.ac.uk/
- Developer Portal: https://uclapi.com/
- Documentation: https://uclapi.com/docs
- GitHub: https://github.com/uclapi
- Source Code: https://github.com/uclapi/uclapi
- OpenAPI: https://github.com/uclapi/uclapi-openapi
- LinkedIn: https://uk.linkedin.com/company/uclapi

## Notes

All entries reflect publicly verifiable sources only; no endpoints or credentials were invented. At review time uclapi.com and uclapi.com/docs returned HTTP 200, the uclapi GitHub org and OpenAPI spec were live, and the UCL Discovery OAI endpoint returned 403 (protected). The `api.uclapi.com` request host did not resolve from the review environment (recorded as status 0) — likely a network egress restriction rather than a confirmed outage. UCL API requires UCL affiliation for authentication and is free of charge.

## Maintainers

- Kin Lane — kin@apievangelist.com
