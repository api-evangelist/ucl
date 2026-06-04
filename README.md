# UCL (ucl)

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
