# Lavu (lavu)

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
