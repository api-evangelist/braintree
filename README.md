# braintree (braintree)

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

Our mission is to empower developers with the tools, resources, and simple-to-use SDKs and APIs to build on one platform, so they can serve merchants from around the world.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/braintree/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/braintree/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-05-19

## APIs

### Braintree Payments API

The Braintree Payments API is the core server-side interface for accepting and processing payments through Braintree's gateway. It enables developers to create and manage transactions, handle authorizations and captures, and process refunds and voids. The API supports a wide range of payment methods including credit and debit cards, PayPal, Apple Pay, Google Pay, and Venmo. Server SDKs are available for Ruby, Python, PHP, Java, Node.js, and .NET to simplify integration with the REST-based API.

- **Human URL:** [https://developer.paypal.com/braintree/docs/](https://developer.paypal.com/braintree/docs/)
- **Base URL:** `https://api.braintreegateway.com`

#### Tags

- Credit Cards
- Payments
- PayPal
- Transactions

#### Properties

- [Documentation](https://developer.paypal.com/braintree/docs/guides/overview)
- [OpenAPI](openapi/braintree-payments-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/braintree-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintree-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Braintree GraphQL API

The Braintree GraphQL API provides a modern, flexible interface for interacting with the Braintree payment gateway. It exposes a single HTTP endpoint that handles all queries and mutations, allowing developers to request only the data they need. The API supports tokenizing payment methods, creating transactions, managing customer vaults, and handling disputes. A sandbox environment is available at payments.sandbox.braintree-api.com/graphql for testing integrations before going live.

- **Human URL:** [https://developer.paypal.com/braintree/graphql/](https://developer.paypal.com/braintree/graphql/)
- **Base URL:** `https://payments.braintree-api.com/graphql`

#### Tags

- GraphQL
- Payment Methods
- Payments
- Transactions

#### Properties

- [Documentation](https://developer.paypal.com/braintree/graphql/guides/concepts/)
- [Postman Collection](collections/braintree-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintree-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/braintree-subscriptions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintree-subscriptions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Braintree JavaScript Client SDK

The Braintree JavaScript Client SDK enables secure collection of payment information directly in the browser without sensitive card data touching your servers. It is organized into standalone modules for different payment methods including hosted fields, PayPal, Apple Pay, Google Pay, and three-D Secure. The SDK provides both a Drop-In UI component for rapid integration and lower-level APIs for fully customized payment forms.

- **Human URL:** [https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/javascript/v3/](https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/javascript/v3/)
- **Base URL:** `https://api.example.com`

#### Tags

- Browser
- Client SDK
- Drop-In UI
- JavaScript
- Payments

#### Properties

- [Documentation](https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/javascript/v3/)
- [Postman Collection](collections/braintree-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintree-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/braintree-subscriptions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintree-subscriptions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Braintree iOS SDK

The Braintree iOS SDK is a native library for accepting card and alternative payments within iOS applications. It supports Swift and Objective-C and provides modules for credit and debit card processing, PayPal, Venmo, Apple Pay, and three-D Secure authentication. The SDK tokenizes payment information collected from users and returns a payment method nonce that your server uses to complete the transaction. It is distributed via CocoaPods, Carthage, and Swift Package Manager.

- **Human URL:** [https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/ios/v6](https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/ios/v6)
- **Base URL:** `https://api.example.com`

#### Tags

- iOS
- Mobile
- Objective-C
- Payments
- Swift

#### Properties

- [Documentation](https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/ios/v6)
- [Postman Collection](collections/braintree-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintree-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/braintree-subscriptions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintree-subscriptions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Braintree Android SDK

The Braintree Android SDK provides a native library for integrating payment acceptance into Android applications. It supports Java and Kotlin and includes modules for card payments, PayPal, Venmo, Google Pay, and three-D Secure verification. Like the iOS counterpart, the Android SDK tokenizes payment data on the client side and returns a payment method nonce for server-side transaction processing. The SDK is distributed through Maven Central and supports Android API level 21 and above.

- **Human URL:** [https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/android/v4](https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/android/v4)
- **Base URL:** `https://api.example.com`

#### Tags

- Android
- Java
- Kotlin
- Mobile
- Payments

#### Properties

- [Documentation](https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/android/v4)
- [Postman Collection](collections/braintree-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintree-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/braintree-subscriptions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintree-subscriptions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Braintree Webhooks

Braintree Webhooks deliver automated HTTP POST notifications to your server when specific events occur within the payment gateway. Supported event types include subscription status changes, transaction settlements, disbursements, dispute openings and resolutions, and sub-merchant account status updates for Braintree Marketplace. Each webhook notification contains the event kind and the full Braintree object associated with the triggering event.

- **Human URL:** [https://developer.paypal.com/braintree/docs/guides/webhooks/overview](https://developer.paypal.com/braintree/docs/guides/webhooks/overview)
- **Base URL:** `https://api.example.com`

#### Tags

- Disputes
- Events
- Notifications
- Subscriptions
- Webhooks

#### Properties

- [Documentation](https://developer.paypal.com/braintree/docs/guides/webhooks/overview)
- [AsyncAPI](asyncapi/braintree-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/braintree-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintree-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/braintree-subscriptions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintree-subscriptions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Braintree Vault API

The Braintree Vault API provides secure, PCI-compliant long-term storage of customer payment method data. It allows merchants to store credit card numbers, PayPal accounts, and other payment methods so that returning customers do not need to re-enter their information. The Vault supports customer records that can hold multiple payment methods, billing addresses, and associated transaction history.

- **Human URL:** [https://developer.paypal.com/braintree/docs/guides/customers/overview](https://developer.paypal.com/braintree/docs/guides/customers/overview)
- **Base URL:** `https://api.braintreegateway.com`

#### Tags

- Customers
- Payment Methods
- PCI Compliance
- Storage
- Vault

#### Properties

- [Documentation](https://developer.paypal.com/braintree/docs/guides/customers/overview)
- [OpenAPI](openapi/braintree-payments-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/braintree-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintree-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Braintree Subscriptions API

The Braintree Subscriptions API enables merchants to manage recurring billing plans and customer subscriptions. Merchants define billing plans with configurable pricing, billing cycles, and trial periods, then subscribe customers using vaulted payment methods. The API handles automatic charge retries, prorated billing for mid-cycle changes, add-ons and discounts, and subscription lifecycle events.

- **Human URL:** [https://developer.paypal.com/braintree/docs/guides/recurring-billing/overview](https://developer.paypal.com/braintree/docs/guides/recurring-billing/overview)
- **Base URL:** `https://api.braintreegateway.com`

#### Tags

- Payments
- Plans
- Recurring Billing
- Subscriptions

#### Properties

- [Documentation](https://developer.paypal.com/braintree/docs/guides/recurring-billing/overview)
- [OpenAPI](openapi/braintree-subscriptions-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/braintree-subscriptions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/braintree-subscriptions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/braintree)
- [LinkedIn](https://www.linkedin.com/company/braintree)
- [JSON-LD](json-ld/braintree-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/braintree-transaction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/braintree-customer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/braintree-subscription-schema.json) — [JSON Schema](https://json-schema.org/specification)
