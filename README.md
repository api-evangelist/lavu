# Lavu

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

Lavu is a cloud-based iPad restaurant point-of-sale system, now positioned as an AI-powered restaurant intelligence platform, serving restaurants, bars, and hospitality businesses with POS, payments, inventory, and reporting. Lavu promotes an open API that lets developers and restaurants extend the point of sale, build peripheral components, and create tailored integrations without waiting on vendor roadmaps. The POSLavu API is a POST-based interface where a single request server accepts form-encoded credentials (dataname, key, token) plus a table selector and returns XML rows; documented tables include menu_groups, menu_categories, menu_items, tables, orders, order_contents, order_payments, ingredients, and ingredient_usage. Records can be written with cmd=insert and an XML contents payload. Credentials are retrieved from the API tab of the POSLavu Control Panel, and the developer documentation is published at admin.poslavu.com; API access comes with an active Lavu account.

**Areas:** Restaurant · Point-of-Sale · Payments · Inventory · Menu Management

## Lavu on APIs.io

Everything profiled for Lavu is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/lavu/](https://apis.io/providers/lavu/)** — or go straight to one of the APIs or properties below.

### APIs (2)

- [Lavu Menu API](https://apis.io/apis/lavu/lavu-menu-api/) — Menu groups, categories, and items.
- [Lavu Orders API](https://apis.io/apis/lavu/lavu-orders-api/) — Orders, order contents, and payments.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Lavu Agentic Access](https://apis.io/agentic-access/lavu/lavu-agentic-access/)

#### JSON Schema (7)

The data models the API reads and writes.

- [MenuCategory](https://apis.io/schemas/lavu/poslavu-api-menu-category/)
- [MenuGroup](https://apis.io/schemas/lavu/poslavu-api-menu-group/)
- [MenuItem](https://apis.io/schemas/lavu/poslavu-api-menu-item/)
- [Order](https://apis.io/schemas/lavu/poslavu-api-order/)
- [OrderContent](https://apis.io/schemas/lavu/poslavu-api-order-content/)
- [OrderPayment](https://apis.io/schemas/lavu/poslavu-api-order-payment/)
- [Table](https://apis.io/schemas/lavu/poslavu-api-table/)

#### JSON Structure (7)

Data models expressed in JSON Structure.

- [Poslavu Api Menu Category Structure](https://apis.io/json-structure/lavu/poslavu-api-menu-category-structure/)
- [Poslavu Api Menu Group Structure](https://apis.io/json-structure/lavu/poslavu-api-menu-group-structure/)
- [Poslavu Api Menu Item Structure](https://apis.io/json-structure/lavu/poslavu-api-menu-item-structure/)
- [Poslavu Api Order Content Structure](https://apis.io/json-structure/lavu/poslavu-api-order-content-structure/)
- [Poslavu Api Order Payment Structure](https://apis.io/json-structure/lavu/poslavu-api-order-payment-structure/)
- [Poslavu Api Order Structure](https://apis.io/json-structure/lavu/poslavu-api-order-structure/)
- [Poslavu Api Table Structure](https://apis.io/json-structure/lavu/poslavu-api-table-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Lavu Poslavu Api Context](https://apis.io/jsonld/lavu/lavu-poslavu-api-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Lavu Vocabulary](https://apis.io/vocabularies/lavu/lavu-vocabulary/)

#### Examples (7)

Example requests and responses.

- [Poslavu Api Menu Category Example](https://apis.io/examples/lavu/poslavu-api-menu-category-example/)
- [Poslavu Api Menu Group Example](https://apis.io/examples/lavu/poslavu-api-menu-group-example/)
- [Poslavu Api Menu Item Example](https://apis.io/examples/lavu/poslavu-api-menu-item-example/)
- [Poslavu Api Order Content Example](https://apis.io/examples/lavu/poslavu-api-order-content-example/)
- [Poslavu Api Order Example](https://apis.io/examples/lavu/poslavu-api-order-example/)
- [Poslavu Api Order Payment Example](https://apis.io/examples/lavu/poslavu-api-order-payment-example/)
- [Poslavu Api Table Example](https://apis.io/examples/lavu/poslavu-api-table-example/)

#### Collections (5)

Postman and Open Collection request collections.

- [Lavu (POSLavu) Inventory API](https://apis.io/collections/lavu/open-lavu-inventory-api/)
- [Lavu (POSLavu) Inventory Menu API](https://apis.io/collections/lavu/open-lavu-menu-api/)
- [Lavu (POSLavu) Inventory Orders API](https://apis.io/collections/lavu/open-lavu-orders-api/)
- [Lavu (POSLavu) API](https://apis.io/collections/lavu/open-lavu-poslavu-api/)
- [Lavu (POSLavu) Inventory Tables API](https://apis.io/collections/lavu/open-lavu-tables-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Lavu — jsonschema rules](https://apis.io/rules/lavu/lavu-jsonschema-spectral-rules/)
- [Lavu API Rules](https://apis.io/rules/lavu/lavu-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Lavu Authentication](https://apis.io/security/lavu/lavu-authentication/)
- [Lavu Domain Security](https://apis.io/security/lavu/lavu-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Lavu Plans Pricing](https://apis.io/plans/lavu/lavu-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Lavu Rate Limits](https://apis.io/rate-limits/lavu/lavu-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Lavu Finops](https://apis.io/finops/lavu/lavu-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://lavu.com)
- [Pricing](https://lavu.com/pricing/)
- [Blog](https://lavu.com/blog/)

## API Evangelist rating

**Kin Score 18.6** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 48.2 |
| Contract quality | 21.3 |
| Contract governance | 27.3 |
| Operational transparency | 5.3 |
| Developer ergonomics | 21.4 |
| Access clarity | 7.9 |

**Agent readiness 22.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
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

**Regulatory alignment 15.2** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/lavu/](https://apis.io/providers/lavu/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Lavu: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/lavu/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
