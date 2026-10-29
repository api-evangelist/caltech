# California Institute of Technology

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

The California Institute of Technology (Caltech) is a private research university in Pasadena, California, and one of the rare institutions in this cohort whose machine-readable footprint is genuinely its own rather than a vendor's contract running under its name. Caltech operates no central developer portal — neither api.caltech.edu nor developer.caltech.edu resolves — and publishes no OpenAPI, no llms.txt, no .well-known catalog and no status page. What it does operate is real research infrastructure on its own domain, engineered by four independent units with no shared convention between them: Caltech Library runs CaltechDATA and CaltechAUTHORS on self-hosted InvenioRDM, with public REST APIs, OAI-PMH 2.0 endpoints and DataCite DOIs minted under Caltech's own 10.22002 prefix; the Seismological Laboratory runs the Southern California Earthquake Data Center's FDSN web services; Caltech/IPAC runs three NASA archives — IRSA, NED and the NASA Exoplanet Archive — behind IVOA Virtual Observatory interfaces; and IMSS runs a Shibboleth identity provider registered in the InCommon federation. Five of the twelve education-regime domain standards are evidenced directly inside live Caltech contracts: shibboleth, saml, oai-pmh, datacite and orcid. The library discovery layer is the one genuinely outsourced surface, a Springshare tenancy at libguides.caltech.edu. The honest summary is that Caltech ships excellent open research data and almost no API product management around it.

**Areas:** University · Higher Education · Education · Private Research University · Institute of Technology · United States · California · Research Data · Open Data · Research Repository · Identity Federation · Astronomy

## California Institute of Technology on APIs.io

Everything profiled for California Institute of Technology is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/caltech/](https://apis.io/providers/caltech/)** — or go straight to one of the APIs or properties below.

### APIs (13)

- [CaltechDATA OAI-PMH](https://apis.io/apis/caltech/caltechdata-oai/) — OAI-PMH 2.0 metadata harvesting endpoint for CaltechDATA. Verified live 2026-08-19 via the Identify verb (repositoryName CaltechDATA, protocolVersion 2.0)…
- [CaltechAUTHORS REST API and OAI-PMH](https://apis.io/apis/caltech/caltechauthors/) — Caltech's institutional publications repository, also on self-hosted InvenioRDM. Exposes the same REST record API and an OAI-PMH 2.0 endpoint, carrying…
- [Caltech Library Feeds](https://apis.io/apis/caltech/library-feeds/) — A metadata service built and operated by Caltech Library (v1.6), harvesting its institutional repositories, public directory and archival systems into…
- [IRSA Virtual Observatory APIs (Caltech/IPAC)](https://apis.io/apis/caltech/irsa-vo/) — The NASA/IPAC Infrared Science Archive exposes IVOA-standard Virtual Observatory interfaces — Table Access Protocol (TAP/ADQL), Simple Cone Search and…
- [NED Table Access Protocol (Caltech/IPAC)](https://apis.io/apis/caltech/ned-tap/) — The NASA/IPAC Extragalactic Database, operated by Caltech/IPAC, exposes an IVOA TAP service over its extragalactic object catalog. Verified live 2026-08-19…
- [NASA Exoplanet Archive TAP (Caltech/IPAC)](https://apis.io/apis/caltech/exoplanet-archive-tap/) — The NASA Exoplanet Archive, operated by Caltech/IPAC, exposes an IVOA TAP service over its confirmed-planet and related tables. Verified live 2026-08-19…
- [Caltech Shibboleth Identity Provider (InCommon)](https://apis.io/apis/caltech/identity-federation/) — Caltech operates its own Shibboleth identity provider at idp.caltech.edu, asserting scoped attributes for caltech.edu. The SAML 2.0 metadata is…
- [Caltech Library Guides (Springshare tenancy)](https://apis.io/apis/caltech/libguides-springshare/) — Caltech Library's discovery and research-guide layer runs on Springshare LibGuides/LibApps rather than on institution-operated software. Recorded as a real…
- [EBSCO Link Resolver (Caltech instance)](https://apis.io/apis/caltech/ebsco-resolver/) — Caltech Library's OpenURL link resolver is an EBSCO tenancy — instance `l7ubco` on the shared host resolver.ebsco.com — referenced from Caltech's own…
- [California Institute of Technology Data Select API](https://apis.io/apis/caltech/caltech-dataselect-api/) — Time-series waveform retrieval (fdsnws-dataselect).
- [California Institute of Technology Event API](https://apis.io/apis/caltech/caltech-event-api/) — Earthquake event catalog queries (fdsnws-event).
- [California Institute of Technology Records API](https://apis.io/apis/caltech/caltech-records-api/) — Published research data records, their metadata, files and DOIs.
- [California Institute of Technology Station API](https://apis.io/apis/caltech/caltech-station-api/) — Station and channel metadata queries (fdsnws-station).

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (2)

The data models the API reads and writes.

- [CaltechDATA Record](https://apis.io/schemas/caltech/caltech-caltechdata-record/)
- [Caltech Library Feeds — Person](https://apis.io/schemas/caltech/caltech-library-feeds-person/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Caltech Context](https://apis.io/jsonld/caltech/caltech-context/)

#### Examples (1)

Example requests and responses.

- [Caltech Caltechdata Record Example](https://apis.io/examples/caltech/caltech-caltechdata-record-example/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [California Institute of Technology API Rules](https://apis.io/rules/caltech/caltech-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Caltech Authentication](https://apis.io/security/caltech/caltech-authentication/)
- [Caltech Domain Security](https://apis.io/security/caltech/caltech-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Caltech Plans Pricing](https://apis.io/plans/caltech/caltech-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Caltech Rate Limits](https://apis.io/rate-limits/caltech/caltech-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Caltech Finops](https://apis.io/finops/caltech/caltech-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.caltech.edu/)
- [Support](https://library.caltech.edu/)
- [Blog](https://www.caltech.edu/about/news)
- [Privacy policy](https://www.caltech.edu/privacy-notice)
- [GitHub](https://github.com/caltechlibrary)

## API Evangelist rating

**Kin Score 22.9** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 23.9 |
| Contract governance | 3.8 |
| Operational transparency | 7.9 |
| Developer ergonomics | 28.6 |
| Access clarity | 15.8 |

**Agent readiness 21.6** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 20.6** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/caltech/](https://apis.io/providers/caltech/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for California Institute of Technology: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/caltech/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
