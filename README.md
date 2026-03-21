# Braintree (braintree)
Braintree is a payment gateway owned by PayPal that enables businesses to accept, process, and split payments in their applications and websites. Braintree provides a full-stack developer platform with server-side APIs, client SDKs for web and mobile, GraphQL support, and tools for managing subscriptions, vaulted payment methods, and webhooks across a wide range of payment methods including credit cards, PayPal, Apple Pay, Google Pay, and Venmo.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/braintree/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Payments, Payment Processing, Transactions, Subscriptions, Mobile, GraphQL

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-03-21

## APIs

### Braintree Payments API
The Braintree Payments API is the core server-side interface for accepting and processing payments through Braintree's gateway. It enables developers to create and manage transactions, handle authorizations and captures, and process refunds and voids. The API supports a wide range of payment methods including credit and debit cards, PayPal, Apple Pay, Google Pay, and Venmo. Server SDKs are available for Ruby, Python, PHP, Java, Node.js, and .NET to simplify integration with the REST-based API.

**Human URL:** [https://developer.paypal.com/braintree/docs/](https://developer.paypal.com/braintree/docs/)


#### Tags:

 - Payments, Transactions, Credit Cards, PayPal

#### Properties

- [Documentation](https://developer.paypal.com/braintree/docs/guides/overview)
- [OpenAPI](openapi/braintree-payments-openapi.yml)

### Braintree GraphQL API
The Braintree GraphQL API provides a modern, flexible interface for interacting with the Braintree payment gateway. It exposes a single HTTP endpoint that handles all queries and mutations, allowing developers to request only the data they need. The API supports tokenizing payment methods, creating transactions, managing customer vaults, and handling disputes. A sandbox environment is available at payments.sandbox.braintree-api.com/graphql for testing integrations before going live.

**Human URL:** [https://developer.paypal.com/braintree/graphql/](https://developer.paypal.com/braintree/graphql/)


#### Tags:

 - GraphQL, Payments, Transactions, Payment Methods

#### Properties

- [Documentation](https://developer.paypal.com/braintree/graphql/guides/concepts/)

### Braintree JavaScript Client SDK
The Braintree JavaScript Client SDK enables secure collection of payment information directly in the browser without sensitive card data touching your servers. It is organized into standalone modules for different payment methods including hosted fields, PayPal, Apple Pay, Google Pay, and three-D Secure. The SDK provides both a Drop-In UI component for rapid integration and lower-level APIs for fully customized payment forms. Collected payment data is exchanged for a payment method nonce that is safely passed to your server for transaction processing.

**Human URL:** [https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/javascript/v3/](https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/javascript/v3/)


#### Tags:

 - JavaScript, Client SDK, Browser, Payments, Drop-In UI

#### Properties

- [Documentation](https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/javascript/v3/)

### Braintree iOS SDK
The Braintree iOS SDK is a native library for accepting card and alternative payments within iOS applications. It supports Swift and Objective-C and provides modules for credit and debit card processing, PayPal, Venmo, Apple Pay, and three-D Secure authentication. The SDK tokenizes payment information collected from users and returns a payment method nonce that your server uses to complete the transaction. It is distributed via CocoaPods, Carthage, and Swift Package Manager.

**Human URL:** [https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/ios/v6](https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/ios/v6)


#### Tags:

 - iOS, Mobile, Swift, Objective-C, Payments

#### Properties

- [Documentation](https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/ios/v6)

### Braintree Android SDK
The Braintree Android SDK provides a native library for integrating payment acceptance into Android applications. It supports Java and Kotlin and includes modules for card payments, PayPal, Venmo, Google Pay, and three-D Secure verification. Like the iOS counterpart, the Android SDK tokenizes payment data on the client side and returns a payment method nonce for server-side transaction processing. The SDK is distributed through Maven Central and supports Android API level 21 and above.

**Human URL:** [https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/android/v4](https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/android/v4)


#### Tags:

 - Android, Mobile, Java, Kotlin, Payments

#### Properties

- [Documentation](https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/android/v4)

### Braintree Webhooks
Braintree Webhooks deliver automated HTTP POST notifications to your server when specific events occur within the payment gateway. Supported event types include subscription status changes, transaction settlements, disbursements, dispute openings and resolutions, and sub-merchant account status updates for Braintree Marketplace. Each webhook notification contains the event kind and the full Braintree object associated with the triggering event. Webhooks are configured in the Braintree Control Panel by specifying a destination URL and selecting the event types to monitor.

**Human URL:** [https://developer.paypal.com/braintree/docs/guides/webhooks/overview](https://developer.paypal.com/braintree/docs/guides/webhooks/overview)


#### Tags:

 - Webhooks, Events, Notifications, Subscriptions, Disputes

#### Properties

- [Documentation](https://developer.paypal.com/braintree/docs/guides/webhooks/overview)
- [AsyncAPI](asyncapi/braintree-webhooks-asyncapi.yml)

### Braintree Vault API
The Braintree Vault API provides secure, PCI-compliant long-term storage of customer payment method data. It allows merchants to store credit card numbers, PayPal accounts, and other payment methods so that returning customers do not need to re-enter their information. The Vault supports customer records that can hold multiple payment methods, billing addresses, and associated transaction history. Stored payment methods can be used directly for recurring billing, subscriptions, and one-click checkout flows.

**Human URL:** [https://developer.paypal.com/braintree/docs/guides/customers/overview](https://developer.paypal.com/braintree/docs/guides/customers/overview)


#### Tags:

 - Vault, Customers, Payment Methods, Storage, PCI Compliance

#### Properties

- [Documentation](https://developer.paypal.com/braintree/docs/guides/customers/overview)
- [OpenAPI](openapi/braintree-payments-openapi.yml)

### Braintree Subscriptions API
The Braintree Subscriptions API enables merchants to manage recurring billing plans and customer subscriptions. Merchants define billing plans with configurable pricing, billing cycles, and trial periods, then subscribe customers using vaulted payment methods. The API handles automatic charge retries, prorated billing for mid-cycle changes, add-ons and discounts, and subscription lifecycle events. Webhook notifications keep your application informed of subscription status changes including successful charges, payment failures, and cancellations.

**Human URL:** [https://developer.paypal.com/braintree/docs/guides/recurring-billing/overview](https://developer.paypal.com/braintree/docs/guides/recurring-billing/overview)


#### Tags:

 - Subscriptions, Recurring Billing, Plans, Payments

#### Properties

- [Documentation](https://developer.paypal.com/braintree/docs/guides/recurring-billing/overview)
- [OpenAPI](openapi/braintree-subscriptions-openapi.yml)

## Common Properties

- [Portal](https://developer.paypal.com/braintree/docs/)
- [Documentation](https://developer.paypal.com/braintree/docs/start/overview)
- [Website](https://www.braintreepayments.com/)
- [Login](https://www.braintreegateway.com/login)
- [Support](https://developer.paypal.com/braintree/docs/support/overview)
- [Blog](https://medium.com/braintree-product-technology)
- [PrivacyPolicy](https://www.paypal.com/us/legalhub/privacy-full)
- [TermsOfService](https://www.braintreepayments.com/legal)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
