# Vantor

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

Maxar Technologies was a publicly traded Earth-imaging and space-systems company formed from the 2017 merger of MacDonald, Dettwiler and Associates (MDA) with DigitalGlobe (founded 1992 in Oakland, California). In December 2022 private-equity firm Advent International agreed to take Maxar private in a USD 6.4 billion cash deal that closed in May 2023, after which Advent split the company into two operating units: Maxar Intelligence (imagery and geospatial software in Westminster, Colorado) and Maxar Space Systems (satellite manufacturing in Palo Alto, California). On 1 October 2025 both units rebranded — Maxar Intelligence became Vantor and Maxar Space Systems became Lanteris Space Systems. On 13 January 2026 Intuitive Machines completed the acquisition of Lanteris from Advent for approximately USD 800 million, leaving Vantor as the sole remaining Advent-owned successor of the Maxar brand. The public developer surface for the original Maxar APIs — imagery search, streaming (WMS/WMTS/WFS), tasking, ordering, monitoring, authentication and account services — is now delivered through the Vantor Hub (hub.vantor.com / pro.maxar.com) and the Maxar Geospatial Platform (MGP) SDKs (Python, Java, R). The Maxar Open Data Program continues to publish a public STAC catalog of pre-/post-event high-resolution imagery on AWS Open Data.

**Areas:** Satellite Imagery · Earth Observation · Geospatial · Remote Sensing · Spatial Intelligence · Defense · Intelligence · WorldView · STAC · OGC · WMS · WMTS

## Vantor on APIs.io

Everything profiled for Vantor is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/vantor/](https://apis.io/providers/vantor/)** — or go straight to one of the APIs or properties below.

### APIs (38)

- [Maxar Vivid Basemap API](https://apis.io/apis/vantor/basemaps/) — Vivid is Maxar's cloud-free, color-balanced basemap product — a global mosaic refreshed from the WorldView archive. The Vivid Basemap API exposes the…
- [Maxar Content Catalog API](https://apis.io/apis/vantor/catalog/) — Legacy Maxar Content Catalog API — the canonical search index against the WorldView / GeoEye / IKONOS / QuickBird archive. Generated from Maxar's published…
- [Maxar Open Data STAC Catalog](https://apis.io/apis/vantor/open-data-stac/) — Free, public STAC (SpatioTemporal Asset Catalog) of pre- and post-event high-resolution Maxar imagery published in support of emergency planning, risk…
- [Maxar Transform API](https://apis.io/apis/vantor/transform-api/) — Transform API exposes image transformation primitives (reproject, tile, mosaic, format-convert) over Maxar imagery. A TypeScript client…
- [Maxar Technologies Authentication / Token Service](https://apis.io/apis/vantor/authentication/) — OAuth2-style token service that mints bearer access tokens (and 180-day default API keys) for use against all Vantor Hub / MGP APIs.
- [Maxar Technologies Streaming Imagery API](https://apis.io/apis/vantor/streaming-imagery/) — OGC-compliant WFS / WMS / WMTS streaming services for delivering online imagery strips into web mapping clients and GIS workflows.
- [Maxar Technologies Streaming Basemap API](https://apis.io/apis/vantor/streaming-basemap/) — OGC service delivering Maxar Vivid basemap products and their metadata for cartographic and analytic use.
- [Maxar Technologies Streaming 3D API](https://apis.io/apis/vantor/streaming-3d/) — Streams 3D surface models derived from Maxar's stereo and tri-stereo collections for visualization and 3D analysis.
- [Maxar Technologies Monitoring API](https://apis.io/apis/vantor/monitoring/) — Register Areas of Interest and receive alerts when new imagery or analytic outputs match. Drives standing tip-and-cue workflows over the Maxar catalog.
- [Maxar Technologies Tasking API](https://apis.io/apis/vantor/tasking/) — Request new imagery collection from the WorldView Legion and legacy WorldView constellations within a target geometry and time window. Supports Fastview and…
- [Maxar Technologies Raster Analytics API](https://apis.io/apis/vantor/raster-analytics/) — Server-side raster processing - band manipulation, classification, and index models (NDVI, NDWI, etc.) - composed as analysis graphs over the Maxar catalog.
- [Maxar Technologies Vector Analytics API](https://apis.io/apis/vantor/vector-analytics/) — Vector deliveries of change monitoring outputs through OGC WMS / WMTS for downstream analytic and GIS consumption.
- [Maxar Technologies Geospatial Platform Python SDK](https://apis.io/apis/vantor/python-sdk/) — Official Python SDK (maxar-platform on PyPI) wrapping the MGP / Vantor Hub APIs for discovery, ordering, monitoring, streaming, and tasking workflows.
- [Maxar Technologies MGP Postman Collection](https://apis.io/apis/vantor/postman/) — Public Postman workspace documenting the Maxar Geospatial Platform API surface for quick exploration and testing.
- [Vantor Accounts API](https://apis.io/apis/vantor/vantor-accounts-api/) — The Accounts API from Vantor — 2 operation(s) for accounts.
- [Vantor API Keys API](https://apis.io/apis/vantor/vantor-api-keys-api/) — The API Keys API from Vantor — 2 operation(s) for api keys.
- [Vantor Authentication API](https://apis.io/apis/vantor/vantor-authentication-api/) — The Authentication API from Vantor — 2 operation(s) for authentication.
- [Vantor Collections API](https://apis.io/apis/vantor/vantor-collections-api/) — Browse and inspect collections
- [Vantor Credits API](https://apis.io/apis/vantor/vantor-credits-api/) — The Credits API from Vantor — 1 operation(s) for credits.
- [Vantor Deliveries API](https://apis.io/apis/vantor/vantor-deliveries-api/) — The Deliveries API from Vantor — 1 operation(s) for deliveries.
- [Vantor Discovery API](https://apis.io/apis/vantor/vantor-discovery-api/) — The Discovery API from Vantor — 5 operation(s) for discovery.
- [Vantor Estimates API](https://apis.io/apis/vantor/vantor-estimates-api/) — The Estimates API from Vantor — 1 operation(s) for estimates.
- [Vantor Events API](https://apis.io/apis/vantor/vantor-events-api/) — The Events API from Vantor — 1 operation(s) for events.
- [Vantor Feasibility API](https://apis.io/apis/vantor/vantor-feasibility-api/) — The Feasibility API from Vantor — 1 operation(s) for feasibility.
- [Vantor Image API](https://apis.io/apis/vantor/vantor-image-api/) — The Image API from Vantor — 1 operation(s) for image.
- [Vantor Introspection API](https://apis.io/apis/vantor/vantor-introspection-api/) — Inspect tokens
- [Vantor Items API](https://apis.io/apis/vantor/vantor-items-api/) — Retrieve individual STAC items
- [Vantor Monitors API](https://apis.io/apis/vantor/vantor-monitors-api/) — The Monitors API from Vantor — 2 operation(s) for monitors.
- [Vantor Ordering API](https://apis.io/apis/vantor/vantor-ordering-api/) — The Ordering API from Vantor — 6 operation(s) for ordering.
- [Vantor Orders API](https://apis.io/apis/vantor/vantor-orders-api/) — The Orders API from Vantor — 2 operation(s) for orders.
- [Vantor Search API](https://apis.io/apis/vantor/vantor-search-api/) — Search and filter imagery and derivatives
- [Vantor Subscriptions API](https://apis.io/apis/vantor/vantor-subscriptions-api/) — The Subscriptions API from Vantor — 1 operation(s) for subscriptions.
- [Vantor Tasks API](https://apis.io/apis/vantor/vantor-tasks-api/) — The Tasks API from Vantor — 2 operation(s) for tasks.
- [Vantor Tokens API](https://apis.io/apis/vantor/vantor-tokens-api/) — Issue and refresh access tokens
- [Vantor Users API](https://apis.io/apis/vantor/vantor-users-api/) — The Users API from Vantor — 2 operation(s) for users.
- [Vantor WFS API](https://apis.io/apis/vantor/vantor-wfs-api/) — The WFS API from Vantor — 1 operation(s) for wfs.
- [Vantor WMS API](https://apis.io/apis/vantor/vantor-wms-api/) — The WMS API from Vantor — 1 operation(s) for wms.
- [Vantor WMTS API](https://apis.io/apis/vantor/vantor-wmts-api/) — The WMTS API from Vantor — 1 operation(s) for wmts.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### GraphQL (1)

GraphQL schemas.

- [Moved to /providers/vantor/](https://apis.io/graphqls/vantor/maxar-technologies-graphql/)

#### Agentic access (2)

Which operations an agent can call, which act, and which need a human in the loop.

- [Maxar Technologies Agentic Access](https://apis.io/agentic-access/vantor/maxar-technologies-agentic-access/)
- [Vantor Agentic Access](https://apis.io/agentic-access/vantor/vantor-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [Maxar Monitor](https://apis.io/schemas/vantor/maxar-technologies-monitor/)
- [Maxar Order](https://apis.io/schemas/vantor/maxar-technologies-order/)
- [Maxar STAC Item](https://apis.io/schemas/vantor/maxar-technologies-stac-item/)
- [Maxar Tasking Request](https://apis.io/schemas/vantor/maxar-technologies-task/)

#### JSON Structure (3)

Data models expressed in JSON Structure.

- [Maxar Technologies Order Structure](https://apis.io/json-structure/vantor/maxar-technologies-order-structure/)
- [Maxar Technologies Stac Item Structure](https://apis.io/json-structure/vantor/maxar-technologies-stac-item-structure/)
- [Maxar Technologies Task Structure](https://apis.io/json-structure/vantor/maxar-technologies-task-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Maxar Technologies Context](https://apis.io/jsonld/vantor/maxar-technologies-context/)

#### Examples (8)

Example requests and responses.

- [Auth Token Request](https://apis.io/examples/vantor/auth-token-request/)
- [Auth Token Response](https://apis.io/examples/vantor/auth-token-response/)
- [Discovery Search Request](https://apis.io/examples/vantor/discovery-search-request/)
- [Discovery Search Response](https://apis.io/examples/vantor/discovery-search-response/)
- [Monitor Create Request](https://apis.io/examples/vantor/monitor-create-request/)
- [Order Place Request](https://apis.io/examples/vantor/order-place-request/)
- [Order Place Response](https://apis.io/examples/vantor/order-place-response/)
- [Task Submit Request](https://apis.io/examples/vantor/task-submit-request/)

#### Collections (49)

Postman and Open Collection request collections.

- [Vantor Hub Account Services API](https://apis.io/collections/vantor/open-admin/)
- [Vantor Hub Authentication API](https://apis.io/collections/vantor/open-authentication/)
- [Vantor Hub Discovery API](https://apis.io/collections/vantor/open-discovery/)
- [Vantor Hub Account Services Accounts API](https://apis.io/collections/vantor/open-maxar-technologies-accounts-api/)
- [Vantor Hub Account Services Accounts API Keys API](https://apis.io/collections/vantor/open-maxar-technologies-api-keys-api/)
- [Vantor Hub Account Services Accounts Collections API](https://apis.io/collections/vantor/open-maxar-technologies-collections-api/)
- [Vantor Hub Account Services Accounts Credits API](https://apis.io/collections/vantor/open-maxar-technologies-credits-api/)
- [Vantor Hub Account Services Accounts Deliveries API](https://apis.io/collections/vantor/open-maxar-technologies-deliveries-api/)
- [Vantor Hub Account Services Accounts Estimates API](https://apis.io/collections/vantor/open-maxar-technologies-estimates-api/)
- [Vantor Hub Account Services Accounts Events API](https://apis.io/collections/vantor/open-maxar-technologies-events-api/)
- [Vantor Hub Account Services Accounts Feasibility API](https://apis.io/collections/vantor/open-maxar-technologies-feasibility-api/)
- [Vantor Hub Account Services Accounts Image API](https://apis.io/collections/vantor/open-maxar-technologies-image-api/)
- [Vantor Hub Account Services Accounts Introspection API](https://apis.io/collections/vantor/open-maxar-technologies-introspection-api/)
- [Vantor Hub Account Services Accounts Items API](https://apis.io/collections/vantor/open-maxar-technologies-items-api/)
- [Vantor Hub Account Services Accounts Monitors API](https://apis.io/collections/vantor/open-maxar-technologies-monitors-api/)
- [Vantor Hub Account Services Accounts Orders API](https://apis.io/collections/vantor/open-maxar-technologies-orders-api/)
- [Vantor Hub Account Services Accounts Search API](https://apis.io/collections/vantor/open-maxar-technologies-search-api/)
- [Vantor Hub Account Services Accounts Subscriptions API](https://apis.io/collections/vantor/open-maxar-technologies-subscriptions-api/)
- [Vantor Hub Account Services Accounts Tasks API](https://apis.io/collections/vantor/open-maxar-technologies-tasks-api/)
- [Vantor Hub Account Services Accounts Tokens API](https://apis.io/collections/vantor/open-maxar-technologies-tokens-api/)
- [Vantor Hub Account Services Accounts Users API](https://apis.io/collections/vantor/open-maxar-technologies-users-api/)
- [Vantor Hub Account Services Accounts WFS API](https://apis.io/collections/vantor/open-maxar-technologies-wfs-api/)
- [Vantor Hub Account Services Accounts WMS API](https://apis.io/collections/vantor/open-maxar-technologies-wms-api/)
- [Vantor Hub Account Services Accounts WMTS API](https://apis.io/collections/vantor/open-maxar-technologies-wmts-api/)
- [Maxar Geospatial Platform Monitoring API](https://apis.io/collections/vantor/open-monitoring/)
- …and 24 more published on APIs.io

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Vantor — maxar technologies jsonschema rules](https://apis.io/rules/vantor/maxar-technologies-jsonschema-spectral-rules/)
- [Vantor — maxar technologies rules](https://apis.io/rules/vantor/maxar-technologies-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Maxar Technologies Authentication](https://apis.io/security/vantor/maxar-technologies-authentication/)
- [Maxar Technologies Domain Security](https://apis.io/security/vantor/maxar-technologies-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Maxar Technologies Plans Pricing](https://apis.io/plans/vantor/maxar-technologies-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Maxar Technologies Rate Limits](https://apis.io/rate-limits/vantor/maxar-technologies-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Maxar Technologies Finops](https://apis.io/finops/vantor/maxar-technologies-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://vantor.com/)
- [Documentation](https://hub.vantor.com/docs/)
- [Changelog](https://hub.vantor.com/docs/release-notes)
- [Blog](https://vantor.com/blog/)
- [Status](https://hub-status.vantor.com/)

## API Evangelist rating

**Kin Score 43.7** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 51.4 |
| Contract governance | 27.3 |
| Operational transparency | 44.7 |
| Developer ergonomics | 54.3 |
| Access clarity | 21.1 |

**Agent readiness 27.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | mostly (partial credit) |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/vantor/](https://apis.io/providers/vantor/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Vantor: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/vantor/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
