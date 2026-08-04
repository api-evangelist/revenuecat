# RevenueCat (revenuecat)

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
