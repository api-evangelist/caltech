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

The California Institute of Technology (Caltech) is a private research university in Pasadena, California. This repository catalogs Caltech's public, machine-readable footprint as an APIs.json profile, under the API Evangelist **university** pipeline — which settles **who operates each surface** before saving any contract.

Caltech is an outlier in the university cohort: its machine-readable surfaces are genuinely **its own**, self-hosted on `caltech.edu`, rather than a vendor's contract running under the institution's name. Nine of eleven catalogued surfaces are institution-operated. Two are vendor tenancies, recorded as relationships with no vendor specification saved here.

There is no central developer portal — neither `api.caltech.edu` nor `developer.caltech.edu` resolves — and Caltech publishes no OpenAPI, `llms.txt`, `.well-known` catalog or status page for any surface.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/caltech/refs/heads/main/apis.yml
- Naftiko Run: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=caltech-api-evangelist&utm_content=repo

## Type

- University / Private Research University — Index / Consumer / 3rd-Party

## Tags

- University
- Higher Education
- Education
- Private Research University
- Institute of Technology
- United States
- California
- Research Data
- Open Data
- Research Repository
- Identity Federation
- Astronomy
- Seismology
- Research Computing
- OAI-PMH

## Surfaces, by operator

Every surface carries an `x-operator` in `apis.yml`. `institution` means Caltech runs the thing the contract describes; `tenant` means the data is Caltech's and the contract is a vendor's.

### Institution-operated (9)

- **CaltechDATA REST API** — Research data repository on self-hosted InvenioRDM. DataCite DOIs under Caltech's own `10.22002` prefix; ORCID iDs on creators. Base: https://data.caltech.edu/api/records
- **CaltechDATA OAI-PMH** — OAI-PMH 2.0 harvesting, advertising `datacite`, `datacite4`, `dcat`, `marc21`, `oai_dc`. Base: https://data.caltech.edu/oai2d
- **CaltechAUTHORS REST API and OAI-PMH** — Publications repository on self-hosted InvenioRDM, carrying ORCID and ROR identifiers. Base: https://authors.library.caltech.edu/api/records
- **Caltech Library Feeds** — Library-built metadata service publishing JSON datasets from its repositories, directory and archives, on its own `irdmtools` toolchain. Base: https://feeds.library.caltech.edu/
- **SCEDC FDSN Web Services** — Southern California Earthquake Data Center, Caltech Seismological Laboratory. `fdsnws-event`, `fdsnws-station`, `fdsnws-dataselect`. Base: https://service.scedc.caltech.edu/fdsnws
- **IRSA Virtual Observatory APIs (Caltech/IPAC)** — NASA/IPAC Infrared Science Archive: IVOA TAP, Simple Cone Search, Simple Image Access v2. Base: https://irsa.ipac.caltech.edu/TAP
- **NED Table Access Protocol (Caltech/IPAC)** — NASA/IPAC Extragalactic Database IVOA TAP. Base: https://ned.ipac.caltech.edu/tap
- **NASA Exoplanet Archive TAP (Caltech/IPAC)** — IVOA TAP over confirmed-planet tables. Base: https://exoplanetarchive.ipac.caltech.edu/TAP
- **Caltech Shibboleth Identity Provider (InCommon)** — SAML 2.0 / Shibboleth IdP, scope `caltech.edu`, registered in InCommon and reachable through eduGAIN. Base: https://idp.caltech.edu/idp/shibboleth

### Vendor tenancies (2) — relationship recorded, no vendor contract saved

- **Caltech Library Guides** — Springshare LibGuides tenancy at https://libguides.caltech.edu/ (site_id 64). Springshare's generic API at `lgapi-us.libapps.com` is **not** saved under Caltech.
- **EBSCO Link Resolver** — EBSCO tenancy (instance `l7ubco`) on a shared vendor host.

## Domain standards (Kin Score `education` regime)

Five of twelve confirmed, each evidenced inside a live contract or response body rather than a prose claim — see [conformance/caltech-education-standards.yml](conformance/caltech-education-standards.yml).

| Standard | Status | Evidence |
|---|---|---|
| `shibboleth` | conformant | `IDPSSODescriptor/@protocolSupportEnumeration` includes `urn:mace:shibboleth:1.0` |
| `saml` | conformant | InCommon-signed metadata, `registrationAuthority` = `https://incommon.org` |
| `oai-pmh` | conformant | `Identify/protocolVersion` = `2.0` on two endpoints |
| `datacite` | conformant | `pids.doi.provider` = `datacite`, Caltech prefix `10.22002` |
| `orcid` | conformant | `creators[].person_or_org.identifiers[].scheme` = `orcid` |
| `crossref`, `scim`, `lti`, `oneroster`, `ed-fi`, `caliper`, `qti` | not found | probed; recorded as absences |

## Artifacts

- OpenAPI (derived, marked `method: derived` — Caltech publishes none): [openapi/](openapi/) with pristine pre-refine copies in [openapi/_original/](openapi/_original/)
- JSON Schema: [json-schema/](json-schema/)
- Examples (verbatim captured responses): [examples/](examples/)
- Conformance: [conformance/caltech-education-standards.yml](conformance/caltech-education-standards.yml)
- Authentication: [authentication/caltech-authentication.yml](authentication/caltech-authentication.yml)
- Errors: [errors/caltech-errors.yml](errors/caltech-errors.yml)
- Lifecycle: [lifecycle/caltech-lifecycle.yml](lifecycle/caltech-lifecycle.yml)
- Vocabulary: [vocabulary/caltech-vocabulary.yml](vocabulary/caltech-vocabulary.yml)
- Governance observations: [rules/caltech-rules.yml](rules/caltech-rules.yml)
- JSON-LD: [json-ld/caltech-context.jsonld](json-ld/caltech-context.jsonld)
- Plans / Rate Limits / FinOps: [plans/](plans/caltech-plans-pricing.yml) · [rate-limits/](rate-limits/caltech-rate-limits.yml) · [finops/](finops/caltech-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-19

## Common Properties

- Website: https://www.caltech.edu/
- Privacy Notice: https://www.caltech.edu/privacy-notice
- GitHub: https://github.com/caltechlibrary · https://github.com/Caltech-IPAC
- Open Data / Research Repository: https://data.caltech.edu/ · https://authors.library.caltech.edu/
- Identity Federation: https://mdq.incommon.org/entities/https%3A%2F%2Fidp.caltech.edu%2Fidp%2Fshibboleth
- Course Catalog: https://catalog.caltech.edu/
- Research Computing: https://hpc.caltech.edu/
- AI Policy: https://www.imss.caltech.edu/services/ai
- LinkedIn: https://www.linkedin.com/school/california-institute-of-technology/
- Review: [review.yml](review.yml)

## Notes

- Every surface was live-verified on 2026-08-19 with a **real query**, not a link check: SCEDC returned actual catalog earthquakes, the IVOA TAP services returned actual rows, and the OAI-PMH endpoints answered the `Identify` verb. No endpoints were fabricated.
- Both OpenAPI documents here are **derived by API Evangelist from live probes** and marked `method: derived`. Caltech publishes no OpenAPI. The only machine-readable service description Caltech itself publishes is a WADL for `fdsnws-dataselect`.
- The `caltech` GitHub org self-identifies as an unofficial community group and is **not** claimed as an institutional property; the substantive code lives under `caltechlibrary` and `Caltech-IPAC`.
- `authors.library.caltech.edu` was previously excluded after an HTTP 522. It verified **200** on 2026-08-19 and is now catalogued — but 522s were still observed between successful calls, and Caltech publishes no status page on which a consumer could confirm that as an incident.
- Bot-blocking is recorded as a finding, not a gap: `scedc.caltech.edu` documentation returns 403 to non-browser clients while its data services return 200, and `www.caltech.edu/about/news` returns 403 while its Atom feed returns 200.

## Maintainers

- Kin Lane — kin@apievangelist.com
