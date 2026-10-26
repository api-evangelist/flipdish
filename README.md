# Flipdish (flipdish)

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

Flipdish is an online ordering and branded-app platform that gives restaurants and takeaways their own websites, mobile apps, kiosks, and order-management tools to take direct, commission-friendly orders. For developers and integration partners, Flipdish exposes a REST API (Flipdish Open API v1.0, base URL https://api.flipdish.co) documented in its Developer Hub, covering stores, orders, menus, catalog, customers, vouchers and campaigns, payouts and payments, apps and channels, devices, and platform resources, plus webhook/event subscriptions. Authentication uses OAuth 2.0 (implicit grant for first-party portal apps; client-credentials for server-to-server App Store apps). A Swagger specification at https://api.flipdish.co/swagger/docs/v1.0 and pre-generated SDKs (C#, Java, PHP, JavaScript, TypeScript, plus a SignalR realtime client) are published from the flipdishbytes GitHub org.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/flipdish/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/flipdish/refs/heads/main/apis.yml)

## Scope

- **Type:** company

## Tags

- Restaurant
- Online Ordering
- Mobile Apps
- Point of Sale
- Orders
- Menu
- Payments
- Webhooks

## Timestamps

- **Created:** 2026-06-02
- **Modified:** 2026-06-02

## APIs

### Flipdish Apps & Channels API

Manage apps, mobile apps, App Store configurations, white-label config and builds, websites, and sales channels.

- **Human URL:** [https://developers.flipdish.com/reference](https://developers.flipdish.com/reference)
- **Base URL:** `https://api.flipdish.co`

#### Tags

- Apps
- Mobile Apps
- App Store
- White Label
- Channels

#### Properties

- [OpenAPI](openapi/flipdish-apps-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flipdish-apps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flipdish-apps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Flipdish Catalog API

Manage catalog groups, items, products, images, changes, and metafield definitions.

- **Human URL:** [https://developers.flipdish.com/reference](https://developers.flipdish.com/reference)
- **Base URL:** `https://api.flipdish.co`

#### Tags

- Catalog
- Products
- Metafields

#### Properties

- [OpenAPI](openapi/flipdish-catalog-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flipdish-catalog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flipdish-catalog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Flipdish Customers & Accounts API

Manage customers, platform users, teammates, accounts, and delivery drivers.

- **Human URL:** [https://developers.flipdish.com/reference](https://developers.flipdish.com/reference)
- **Base URL:** `https://api.flipdish.co`

#### Tags

- Customers
- Users
- Teammates
- Accounts
- Drivers

#### Properties

- [OpenAPI](openapi/flipdish-customers-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flipdish-customers.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flipdish-customers.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Flipdish Devices API

Manage card readers, kiosk and terminal IoT devices, and device heartbeats.

- **Human URL:** [https://developers.flipdish.com/reference](https://developers.flipdish.com/reference)
- **Base URL:** `https://api.flipdish.co`

#### Tags

- Card Readers
- Kiosks
- Terminals
- Devices

#### Properties

- [OpenAPI](openapi/flipdish-devices-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flipdish-devices.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flipdish-devices.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Flipdish Marketing API

Run marketing campaigns, vouchers, cross-sell, and push notifications.

- **Human URL:** [https://developers.flipdish.com/reference](https://developers.flipdish.com/reference)
- **Base URL:** `https://api.flipdish.co`

#### Tags

- Campaigns
- Vouchers
- Push Notifications

#### Properties

- [OpenAPI](openapi/flipdish-marketing-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flipdish-marketing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flipdish-marketing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Flipdish Menus API

Build and maintain menus, sections, items, option sets, zones, and nutrition information.

- **Human URL:** [https://developers.flipdish.com/reference](https://developers.flipdish.com/reference)
- **Base URL:** `https://api.flipdish.co`

#### Tags

- Menus
- Menu Sections
- Option Sets
- Nutrition

#### Properties

- [OpenAPI](openapi/flipdish-menus-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flipdish-menus.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flipdish-menus.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Flipdish Orders API

Retrieve, batch, and manage orders, tips, and fulfillment state configuration for online ordering.

- **Human URL:** [https://developers.flipdish.com/reference](https://developers.flipdish.com/reference)
- **Base URL:** `https://api.flipdish.co`

#### Tags

- Orders
- Order Batches
- Tips
- Fulfillment

#### Properties

- [OpenAPI](openapi/flipdish-orders-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flipdish-orders.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flipdish-orders.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Flipdish Payments & Payouts API

Handle payouts, payout reports, bank accounts, Stripe Custom Connect, invoices, payments, and subscriptions.

- **Human URL:** [https://developers.flipdish.com/reference](https://developers.flipdish.com/reference)
- **Base URL:** `https://api.flipdish.co`

#### Tags

- Payouts
- Invoices
- Stripe Connect
- Subscriptions

#### Properties

- [OpenAPI](openapi/flipdish-payments-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flipdish-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flipdish-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Flipdish Platform API

Cross-cutting platform surface: webhooks, events, OAuth clients, authorization tokens, audit logs, onboarding, features, and integrations.

- **Human URL:** [https://developers.flipdish.com/reference](https://developers.flipdish.com/reference)
- **Base URL:** `https://api.flipdish.co`

#### Tags

- Webhooks
- Events
- OAuth Clients
- Audit Logs

#### Properties

- [OpenAPI](openapi/flipdish-platform-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flipdish-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flipdish-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Flipdish Stores API

Manage stores, store groups, locations, delivery zones, and store order capacity across a Flipdish brand.

- **Human URL:** [https://developers.flipdish.com/reference](https://developers.flipdish.com/reference)
- **Base URL:** `https://api.flipdish.co`

#### Tags

- Stores
- Locations
- Delivery Zones
- Addresses

#### Properties

- [OpenAPI](openapi/flipdish-stores-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flipdish-stores.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flipdish-stores.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.flipdish.com)
- [Documentation](https://developers.flipdish.com/)
- [API Reference](https://developers.flipdish.com/reference)
- [Getting Started](https://developers.flipdish.com/docs/getting-started)
- [Authentication](https://developers.flipdish.com/docs/getting-started)
- [OpenAPI](https://api.flipdish.co/swagger/docs/v1.0) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Pricing](https://www.flipdish.com/pricing)
- [Sign Up](https://portal.flipdish.com/signup)
- [Login](https://portal.flipdish.com)
- [Support](https://help.flipdish.com)
- [Blog](https://www.flipdish.com/resources/blog)
- [GitHub Organization](https://github.com/flipdish)
- [GitHub Organization](https://github.com/flipdishbytes)
- [SDK](https://www.nuget.org/packages/Flipdish/)
- [SDK](https://www.nuget.org/packages/Flipdish.Core/)
- [SDK](https://github.com/flipdishbytes/api-client-java)
- [SDK](https://github.com/flipdishbytes/api-client-php)
- [SDK](https://www.npmjs.com/package/@flipdish/api-client-javascript)
- [SDK](https://www.npmjs.com/package/@flipdish/api-client-typescript)
- [SDK](https://www.npmjs.com/package/@flipdish/api-client-typescript-signalr)
- [Code Examples](https://github.com/flipdishbytes/integration-examples)
- [Tools](https://github.com/flipdishbytes/spectral-rules)
- [L L Ms Txt](https://developers.flipdish.com/llms.txt)
- [LinkedIn](https://ie.linkedin.com/company/flipdish)
- [X (Twitter)](https://twitter.com/flipdish)
- [Plans](plans/flipdish-plans-pricing.yml)
- [Rate Limits](rate-limits/flipdish-rate-limits.yml)
- [Fin Ops](finops/flipdish-finops.yml)
- [Rules](rules/flipdish-spectral-rules.yml)
- [Vocabulary](vocabulary/flipdish-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
