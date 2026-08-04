# Lavu (lavu)

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

Lavu is a cloud-based iPad restaurant point-of-sale system, now positioned as an AI-powered restaurant intelligence platform, serving restaurants, bars, and hospitality businesses with POS, payments, inventory, and reporting. Lavu promotes an open API that lets developers and restaurants extend the point of sale, build peripheral components, and create tailored integrations without waiting on vendor roadmaps. The POSLavu API is a POST-based interface where a single request server accepts form-encoded credentials (dataname, key, token) plus a table selector and returns XML rows; documented tables include menu_groups, menu_categories, menu_items, tables, orders, order_contents, order_payments, ingredients, and ingredient_usage. Records can be written with cmd=insert and an XML contents payload. Credentials are retrieved from the API tab of the POSLavu Control Panel, and the developer documentation is published at admin.poslavu.com; API access comes with an active Lavu account.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lavu/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lavu/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Restaurant
- Point of Sale
- Payments
- Inventory
- Menu Management

## Timestamps

- **Created:** 2026-06-02
- **Modified:** 2026-06-02

## APIs

### Lavu (POSLavu) API

A POST-based data API for the Lavu restaurant POS. A single request server accepts form-encoded dataname, key, token, and table parameters and returns XML rows; reads support column/value exact-match filters, value_min/value_max range filters, and limit (offset,count) pagination, while cmd=insert writes XML row payloads. Documented tables include menu_groups, menu_categories, menu_items, tables, orders, order_contents, order_payments, ingredients, and ingredient_usage. Credentials come from the API tab of the POSLavu Control Panel.

#### Tags

- Point of Sale
- Orders
- Menu
- Inventory

#### Properties

- [Documentation](https://admin.poslavu.com/cp/areas/api_doc.html)
- [Documentation](https://lavu.com/integrations/)
- [OpenAPI](openapi/lavu-poslavu-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lavu-poslavu-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lavu-poslavu-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://lavu.com)
- [Blog](https://lavu.com/blog/)
- [Pricing](https://lavu.com/pricing/)
- [LinkedIn](https://www.linkedin.com/company/lavu-inc)
- [Plans](plans/lavu-plans-pricing.yml)
- [Rate Limits](rate-limits/lavu-rate-limits.yml)
- [Fin Ops](finops/lavu-finops.yml)
- [Rules](rules/lavu-spectral-rules.yml)
- [Vocabulary](vocabulary/lavu-vocabulary.yaml)
- [JSON-LD](json-ld/lavu-poslavu-api-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
