# California Institute of Technology (caltech)

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
