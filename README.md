# California Institute of Technology (caltech)

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

The California Institute of Technology (Caltech) is a private research university in Pasadena, California, ranked #10 in the QS World University Rankings 2025. This repository catalogs Caltech's public, machine-readable developer/API footprint as an APIs.json profile. Caltech has no single unified institution-wide developer portal; its verifiable public APIs are concentrated in research-data infrastructure (CaltechDATA, on InvenioRDM) and astronomy infrastructure (the Caltech/IPAC NASA Infrared Science Archive, IRSA).

- APIs.json: https://raw.githubusercontent.com/api-evangelist/caltech/refs/heads/main/apis.yml
- Naftiko Run: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=caltech-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

- Education
- Higher Education
- University
- Research Data
- Astronomy
- Open Data
- United States

## APIs

- **CaltechDATA REST API** — InvenioRDM REST API for the Caltech research data repository (records, metadata, files, DOIs). Docs: https://caltechlibrary.github.io/caltechdata_api/ · Base: https://data.caltech.edu/api/records · Code: https://github.com/caltechlibrary/caltechdata_api
- **CaltechDATA OAI-PMH** — Metadata harvesting endpoint for CaltechDATA. Docs: https://data.caltech.edu/ · Base: https://data.caltech.edu/oai2d
- **IRSA Virtual Observatory APIs (IPAC)** — IVOA-standard TAP, Simple Cone Search, and Simple Image Access APIs over NASA infrared/submillimeter catalogs and images. Docs: https://irsa.ipac.caltech.edu/voapi.html · Base: https://irsa.ipac.caltech.edu/TAP · Code: https://github.com/Caltech-IPAC

## Plans / Rate Limits / FinOps

- Plans: [plans/caltech-plans-pricing.yml](plans/caltech-plans-pricing.yml)
- Rate Limits: [rate-limits/caltech-rate-limits.yml](rate-limits/caltech-rate-limits.yml)
- FinOps: [finops/caltech-finops.yml](finops/caltech-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.caltech.edu/
- GitHub: https://github.com/caltechlibrary
- LinkedIn: https://www.linkedin.com/school/california-institute-of-technology/
- Review: [review.yml](review.yml)

## Notes

- All cataloged APIs were live-verified at review time: CaltechDATA REST API (HTTP 200, JSON record hits), CaltechDATA OAI-PMH (HTTP 200 via Identify), and IRSA TAP sync (HTTP 200). No endpoints were fabricated.
- The official `caltech` GitHub org self-identifies as an unofficial community group (1 repo) and points to gitlab.caltech.edu for official resources; the substantive open-source code lives under `caltechlibrary` and `Caltech-IPAC`.
- The legacy `authors.library.caltech.edu` repository was gated/unreachable (HTTP 522) at review time and was not cataloged.

## Maintainers

- Kin Lane — kin@apievangelist.com
