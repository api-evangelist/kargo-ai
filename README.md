# Kargo

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

Kargo (Kargo Technologies, kargo.ai) builds an AI-powered smart loading dock for warehouses and distribution centers. Camera towers (Kargo Tower) and forklift-mounted cameras (Kargo Lift) apply computer vision to every pallet that moves through a dock door, reading LPN, SKU, lot code and expiration-date labels to automate shipping and receiving, verify loads and shipments, detect damage, and feed inventory visibility, shelf-life management, FSMA traceability, claims management, financial reconciliation and automated ASNs back into the customer WMS. Kargo publishes a public integration surface for that data exchange: a REST Document Intake API described by an OpenAPI 3.1 document, a public GraphQL API with open anonymous introspection, a single unified JSON endpoint, a webhook (push) API at shipment and pallet level plus a GraphQL subscription alternative, and flat-file ingest over email, SFTP or AS2. All programmatic access is Auth0 OAuth 2.0 client-credentials bearer tokens.

**Areas:** Company · Logistics · Supply Chain · Warehouse · Computer Vision · Artificial Intelligence · Shipping · Inventory · Industrial Automation · Freight · GraphQL · Webhook

## Kargo on APIs.io

Everything profiled for Kargo is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/kargo-ai/](https://apis.io/providers/kargo-ai/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [Kargo Public GraphQL API](https://apis.io/apis/kargo-ai/kargo-public-graphql-api/) — Kargo's original public integration method, maintained for existing integrations and still the surface behind the Unified Endpoint API. Exposes queries for…
- [Kargo Documents API](https://apis.io/apis/kargo-ai/kargo-ai-documents-api/) — The Documents API from Kargo — 1 operation(s) for documents.
- [Kargo SKU Master API](https://apis.io/apis/kargo-ai/kargo-ai-sku-master-api/) — The SKU Master API from Kargo — 1 operation(s) for sku master.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Kargo Push Webhooks](https://apis.io/asyncapis/kargo-ai/kargo-push-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [kargo](https://apis.io/servers/kargo-ai/kargo/)

#### Collections (1)

Postman and Open Collection request collections.

- [Kargo Public GraphQL API](https://apis.io/collections/kargo-ai/postman-kargo-public-graphql/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Kargo Document Intake Overlay](https://apis.io/overlays/kargo-ai/kargo-document-intake-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Kargo Authentication](https://apis.io/security/kargo-ai/kargo-authentication/)
- [Kargo Domain Security](https://apis.io/security/kargo-ai/kargo-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Kargo Scopes](https://apis.io/scopes/kargo-ai/kargo-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Kargo Plans Pricing](https://apis.io/plans/kargo-ai/kargo-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Kargo Rate Limits](https://apis.io/rate-limits/kargo-ai/kargo-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.kargo.ai/)
- [Documentation](https://docs.kargo.ai/)
- [Getting started](https://docs.kargo.ai/basic_examples)
- [API reference](https://api.kargo.zone/v1/docs/)
- [Sign up](https://athena.mykargo.com/)
- [Support](https://info.mykargo.com/demo)
- [Blog](https://www.kargo.ai/blog)
- [Terms of service](https://www.kargo.ai/terms-of-service)
- [Privacy policy](https://www.kargo.ai/privacy-policy)
- [GitHub](https://github.com/mykargo)

## API Evangelist rating

**Kin Score 54.0** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 67.4 |
| Contract governance | 18.2 |
| Operational transparency | 13.2 |
| Developer ergonomics | 70.8 |
| Access clarity | 34.2 |

**Agent readiness 50.9** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | served (partial credit) |
| Idempotency | documented (partial credit) |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 31.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/kargo-ai/](https://apis.io/providers/kargo-ai/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Kargo: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/kargo-ai/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
