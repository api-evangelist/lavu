# Lavu (lavu)

Lavu is a cloud-based iPad restaurant point-of-sale system, now positioned as an AI-powered restaurant intelligence platform, serving restaurants, bars, and hospitality businesses with POS, payments, inventory, and reporting. Lavu promotes an open API that lets developers and restaurants extend the point of sale, build peripheral components, and create tailored integrations without waiting on vendor roadmaps. The POSLavu API is a POST-based interface where a single request server accepts form-encoded credentials (dataname, key, token) plus a table selector and returns XML rows; documented tables include menu_groups, menu_categories, menu_items, tables, orders, order_contents, order_payments, ingredients, and ingredient_usage. Records can be written with cmd=insert and an XML contents payload. Credentials are retrieved from the API tab of the POSLavu Control Panel, and the developer documentation is published at admin.poslavu.com; API access comes with an active Lavu account.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/lavu/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Restaurant, Point of Sale, Payments, Inventory, Menu Management

## Timestamps

- **Created:** 2026-06-02
- **Modified:** 2026-06-02

## APIs

### Lavu (POSLavu) API

A POST-based data API for the Lavu restaurant POS. A single request server accepts form-encoded dataname, key, token, and table parameters and returns XML rows; reads support column/value exact-match filters, value_min/value_max range filters, and limit (offset,count) pagination, while cmd=insert writes XML row payloads. Documented tables include menu_groups, menu_categories, menu_items, tables, orders, order_contents, order_payments, ingredients, and ingredient_usage. Credentials come from the API tab of the POSLavu Control Panel.

#### Tags:

 - Point of Sale, Orders, Menu, Inventory

#### Properties

- [Documentation](https://admin.poslavu.com/cp/areas/api_doc.html)
- [Documentation](https://lavu.com/integrations/)
- [OpenAPI](openapi/lavu-poslavu-api.yml)
- [NaftikoCapability](capabilities/poslavu-api-menu.yaml)
- [NaftikoCapability](capabilities/poslavu-api-tables.yaml)
- [NaftikoCapability](capabilities/poslavu-api-orders.yaml)
- [NaftikoCapability](capabilities/poslavu-api-inventory.yaml)

## Common Properties

- [Website](https://lavu.com)
- [Blog](https://lavu.com/blog/)
- [Pricing](https://lavu.com/pricing/)
- [LinkedIn](https://www.linkedin.com/company/lavu-inc)
- [Plans](plans/lavu-plans-pricing.yml)
- [RateLimits](rate-limits/lavu-rate-limits.yml)
- [FinOps](finops/lavu-finops.yml)
- [Rules](rules/lavu-spectral-rules.yml)
- [Vocabulary](vocabulary/lavu-vocabulary.yaml)
- [JSONLD](json-ld/lavu-poslavu-api-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Open API | POST-based table query and insert API for extending the POS and building peripheral components and integrations. |
| Menu Management | Read menu groups, categories, and items, and insert new menu items. |
| Order Management | Read orders, line items, and payments, and insert new orders, order contents, and payments. |
| Floor Layout | Read the restaurant floor table layout (coordinates, shapes, names). |
| Inventory | Read ingredients and ingredient usage data. |
| Payment Processing | Integrated card payment processing with dual-pricing / cash-discount options to offset card fees. |

## Use Cases

| Name | Description |
|------|-------------|
| Sales Reporting and Reconciliation | Pull orders, order_contents, and order_payments to reconcile sales and payment volume against the POS and accounting systems. |
| Custom Online Ordering | Read menu structure and insert orders to power a custom or third-party online ordering experience on top of Lavu. |
| Inventory and Recipe Costing | Read ingredients and ingredient_usage to feed inventory tracking and recipe-costing tools. |
| Peripheral Integrations | Build tailored integrations and peripheral components against the open POSLavu API without waiting on vendor roadmaps. |

## Integrations

| Name | Description |
|------|-------------|
| QuickBooks | Accounting integration. |
| Xero | Accounting integration. |
| Restaurant365 | Restaurant accounting and operations integration. |
| DoorDash | Online ordering and delivery integration. |
| Grubhub | Online ordering and delivery integration. |
| Uber Eats | Online ordering and delivery integration. |
| Otter | Online ordering aggregation integration. |
| Chowly | Online ordering aggregation integration. |
| OpenTable | Reservations and loyalty integration. |
| Marketman | Inventory management integration. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Lavu (POSLavu) API](openapi/lavu-poslavu-api.yml)

### JSON Schema

- [poslavu-api-menu-group-schema.json](json-schema/poslavu-api-menu-group-schema.json)
- [poslavu-api-menu-category-schema.json](json-schema/poslavu-api-menu-category-schema.json)
- [poslavu-api-menu-item-schema.json](json-schema/poslavu-api-menu-item-schema.json)
- [poslavu-api-table-schema.json](json-schema/poslavu-api-table-schema.json)
- [poslavu-api-order-schema.json](json-schema/poslavu-api-order-schema.json)
- [poslavu-api-order-content-schema.json](json-schema/poslavu-api-order-content-schema.json)
- [poslavu-api-order-payment-schema.json](json-schema/poslavu-api-order-payment-schema.json)

### JSON Structure

- [poslavu-api-menu-group-structure.json](json-structure/poslavu-api-menu-group-structure.json)
- [poslavu-api-menu-category-structure.json](json-structure/poslavu-api-menu-category-structure.json)
- [poslavu-api-menu-item-structure.json](json-structure/poslavu-api-menu-item-structure.json)
- [poslavu-api-table-structure.json](json-structure/poslavu-api-table-structure.json)
- [poslavu-api-order-structure.json](json-structure/poslavu-api-order-structure.json)
- [poslavu-api-order-content-structure.json](json-structure/poslavu-api-order-content-structure.json)
- [poslavu-api-order-payment-structure.json](json-structure/poslavu-api-order-payment-structure.json)

### JSON-LD

- [lavu-poslavu-api-context.jsonld](json-ld/lavu-poslavu-api-context.jsonld)

### Examples

- [poslavu-api-menu-group-example.json](examples/poslavu-api-menu-group-example.json)
- [poslavu-api-menu-category-example.json](examples/poslavu-api-menu-category-example.json)
- [poslavu-api-menu-item-example.json](examples/poslavu-api-menu-item-example.json)
- [poslavu-api-table-example.json](examples/poslavu-api-table-example.json)
- [poslavu-api-order-example.json](examples/poslavu-api-order-example.json)
- [poslavu-api-order-content-example.json](examples/poslavu-api-order-content-example.json)
- [poslavu-api-order-payment-example.json](examples/poslavu-api-order-payment-example.json)

## Capabilities

Naftiko capabilities organized as self-contained per-surface definitions, each exposing one REST adapter and one MCP adapter.

| Capability | API | Tools |
|------------|-----|-------|
| [Lavu (POSLavu) API — Menu](capabilities/poslavu-api-menu.yaml) | Lavu (POSLavu) API | 2 |
| [Lavu (POSLavu) API — Tables](capabilities/poslavu-api-tables.yaml) | Lavu (POSLavu) API | 1 |
| [Lavu (POSLavu) API — Orders](capabilities/poslavu-api-orders.yaml) | Lavu (POSLavu) API | 2 |
| [Lavu (POSLavu) API — Inventory](capabilities/poslavu-api-inventory.yaml) | Lavu (POSLavu) API | 2 |

## Vocabulary

- [Lavu Vocabulary](vocabulary/lavu-vocabulary.yaml) — Unified taxonomy mapping 9 resources, 2 actions, 4 workflows, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Lavu Spectral Rules](rules/lavu-spectral-rules.yml) — 31 rules across 9 categories enforcing Lavu POSLavu API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
