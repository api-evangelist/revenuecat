# RevenueCat (revenuecat)

RevenueCat provides in-app subscription and purchase infrastructure for mobile and web apps. It abstracts App Store, Google Play, Amazon, Stripe, Roku, and Paddle billing behind cross-platform SDKs and a REST API, handling receipt validation, entitlements, subscriber state, offerings and paywalls, experiments, and subscription analytics. A v1 REST API manages live subscribers and purchases; a v2 REST API manages the project catalog (projects, apps, products, entitlements, offerings, packages); webhooks stream subscription lifecycle events.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/revenuecat/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/revenuecat/refs/heads/main/apis.yml)

## Tags

- Subscriptions
- In-App Purchases
- Billing
- Mobile
- Entitlements

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### RevenueCat Subscribers API

v1 endpoints to get or create a subscriber, delete a subscriber, and read entitlements, subscriptions, and non-subscription purchases for an App User ID.

- **Human URL:** [https://www.revenuecat.com/docs/api-v1](https://www.revenuecat.com/docs/api-v1)
- **Base URL:** `https://api.revenuecat.com/v1`

#### Tags

- Subscribers
- Customers
- App User ID

#### Properties

- [Documentation](https://www.revenuecat.com/docs/api-v1#tag/customers)
- [API Reference](https://www.revenuecat.com/docs/api-v1)
- [OpenAPI](openapi/revenuecat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/revenuecat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/revenuecat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RevenueCat Purchases & Receipts API

v1 receipt validation (POST /receipts) across App Store, Google Play, Amazon, Stripe, Roku, and Paddle, plus transaction refund, defer, cancel, and extend operations.

- **Human URL:** [https://www.revenuecat.com/docs/api-v1#tag/transactions](https://www.revenuecat.com/docs/api-v1#tag/transactions)
- **Base URL:** `https://api.revenuecat.com/v1`

#### Tags

- Purchases
- Receipts
- Transactions

#### Properties

- [Documentation](https://www.revenuecat.com/docs/api-v1#tag/transactions)
- [OpenAPI](openapi/revenuecat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/revenuecat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/revenuecat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RevenueCat Entitlements API (v1)

v1 promotional entitlement operations - grant a complimentary entitlement to a subscriber for a fixed duration and revoke promotional grants.

- **Human URL:** [https://www.revenuecat.com/docs/api-v1#tag/entitlements](https://www.revenuecat.com/docs/api-v1#tag/entitlements)
- **Base URL:** `https://api.revenuecat.com/v1`

#### Tags

- Entitlements
- Promotional
- Grants

#### Properties

- [Documentation](https://www.revenuecat.com/docs/api-v1#tag/entitlements)
- [OpenAPI](openapi/revenuecat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/revenuecat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/revenuecat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RevenueCat Offerings API (v1)

v1 endpoints to fetch the offerings (and packages) resolved for a subscriber - including experiment and targeting evaluation - and to override or clear the current offering for a user.

- **Human URL:** [https://www.revenuecat.com/docs/api-v1#tag/offerings](https://www.revenuecat.com/docs/api-v1#tag/offerings)
- **Base URL:** `https://api.revenuecat.com/v1`

#### Tags

- Offerings
- Paywalls
- Targeting

#### Properties

- [Documentation](https://www.revenuecat.com/docs/api-v1#tag/offerings)
- [OpenAPI](openapi/revenuecat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/revenuecat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/revenuecat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RevenueCat Customer Attributes API

v1 endpoint to set or update custom and reserved subscriber attributes (POST /subscribers/{app_user_id}/attributes) for segmentation, attribution, and messaging.

- **Human URL:** [https://www.revenuecat.com/docs/api-v1#tag/customers/operation/attributes](https://www.revenuecat.com/docs/api-v1#tag/customers/operation/attributes)
- **Base URL:** `https://api.revenuecat.com/v1`

#### Tags

- Attributes
- Customer Data
- Segmentation

#### Properties

- [Documentation](https://www.revenuecat.com/docs/customers/customer-attributes)
- [OpenAPI](openapi/revenuecat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/revenuecat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/revenuecat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RevenueCat Projects API (v2)

v2 endpoints to list the projects an API key can access - the top-level container for apps, products, entitlements, offerings, and customers.

- **Human URL:** [https://www.revenuecat.com/docs/api-v2#tag/Project](https://www.revenuecat.com/docs/api-v2#tag/Project)
- **Base URL:** `https://api.revenuecat.com/v2`

#### Tags

- Projects
- Configuration

#### Properties

- [Documentation](https://www.revenuecat.com/docs/api-v2#tag/Project)
- [OpenAPI](openapi/revenuecat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/revenuecat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/revenuecat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RevenueCat Apps API (v2)

v2 CRUD for apps - the per-store integrations (App Store, Play Store, Amazon, Stripe, and more) inside a project.

- **Human URL:** [https://www.revenuecat.com/docs/api-v2#tag/App](https://www.revenuecat.com/docs/api-v2#tag/App)
- **Base URL:** `https://api.revenuecat.com/v2`

#### Tags

- Apps
- Store Integrations

#### Properties

- [Documentation](https://www.revenuecat.com/docs/api-v2#tag/App)
- [OpenAPI](openapi/revenuecat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/revenuecat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/revenuecat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RevenueCat Customers API (v2)

v2 endpoints to list, create, retrieve, and delete customers within a project, with active entitlements and subscription state.

- **Human URL:** [https://www.revenuecat.com/docs/api-v2#tag/Customer](https://www.revenuecat.com/docs/api-v2#tag/Customer)
- **Base URL:** `https://api.revenuecat.com/v2`

#### Tags

- Customers
- Subscribers

#### Properties

- [Documentation](https://www.revenuecat.com/docs/api-v2#tag/Customer)
- [OpenAPI](openapi/revenuecat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/revenuecat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/revenuecat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RevenueCat Products API (v2)

v2 CRUD for products - the store-mapped subscription and one-time purchase SKUs that back entitlements and packages.

- **Human URL:** [https://www.revenuecat.com/docs/api-v2#tag/Product](https://www.revenuecat.com/docs/api-v2#tag/Product)
- **Base URL:** `https://api.revenuecat.com/v2`

#### Tags

- Products
- Catalog

#### Properties

- [Documentation](https://www.revenuecat.com/docs/api-v2#tag/Product)
- [OpenAPI](openapi/revenuecat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/revenuecat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/revenuecat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RevenueCat Entitlements API (v2)

v2 CRUD for entitlement definitions - the named access levels that products unlock and that gate premium features.

- **Human URL:** [https://www.revenuecat.com/docs/api-v2#tag/Entitlement](https://www.revenuecat.com/docs/api-v2#tag/Entitlement)
- **Base URL:** `https://api.revenuecat.com/v2`

#### Tags

- Entitlements
- Access Levels

#### Properties

- [Documentation](https://www.revenuecat.com/docs/api-v2#tag/Entitlement)
- [OpenAPI](openapi/revenuecat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/revenuecat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/revenuecat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RevenueCat Offerings API (v2)

v2 CRUD for offering definitions - the configurable sets of packages presented on paywalls, including the current offering flag.

- **Human URL:** [https://www.revenuecat.com/docs/api-v2#tag/Offering](https://www.revenuecat.com/docs/api-v2#tag/Offering)
- **Base URL:** `https://api.revenuecat.com/v2`

#### Tags

- Offerings
- Paywalls

#### Properties

- [Documentation](https://www.revenuecat.com/docs/api-v2#tag/Offering)
- [OpenAPI](openapi/revenuecat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/revenuecat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/revenuecat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RevenueCat Packages API (v2)

v2 CRUD for packages - the duration-typed purchase options (monthly, annual, lifetime) within an offering that map products to display positions.

- **Human URL:** [https://www.revenuecat.com/docs/api-v2#tag/Package](https://www.revenuecat.com/docs/api-v2#tag/Package)
- **Base URL:** `https://api.revenuecat.com/v2`

#### Tags

- Packages
- Pricing

#### Properties

- [Documentation](https://www.revenuecat.com/docs/api-v2#tag/Package)
- [OpenAPI](openapi/revenuecat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/revenuecat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/revenuecat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RevenueCat Webhooks

Outbound webhooks that POST subscription lifecycle events (INITIAL_PURCHASE, RENEWAL, CANCELLATION, EXPIRATION, BILLING_ISSUE, PRODUCT_CHANGE, and more) to a customer endpoint, secured with an Authorization header.

- **Human URL:** [https://www.revenuecat.com/docs/integrations/webhooks](https://www.revenuecat.com/docs/integrations/webhooks)
- **Base URL:** `https://api.revenuecat.com/v1`

#### Tags

- Webhooks
- Events
- Lifecycle

#### Properties

- [Documentation](https://www.revenuecat.com/docs/integrations/webhooks)
- [Documentation](https://www.revenuecat.com/docs/integrations/webhooks/event-types-and-fields)

## Common Properties

- [GitHub Organization](https://github.com/RevenueCat)
- [LinkedIn](https://www.linkedin.com/company/revenuecat)
- [Website](https://www.revenuecat.com/)
- [Documentation](https://www.revenuecat.com/docs)
- [Plans](plans/revenuecat-plans-pricing.yml)
- [Rate Limits](rate-limits/revenuecat-rate-limits.yml)
- [Fin Ops](finops/revenuecat-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
