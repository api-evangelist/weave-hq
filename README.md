# Weave (weave-hq)

Weave is an all-in-one customer and patient communication and payments platform for small healthcare businesses - dental, optometry, veterinary, medical, audiology, and specialty practices. It unifies VoIP phone, two-way texting, online scheduling, digital forms, payments (text-to-pay), review generation, and email into a single system that syncs with practice management and EHR software. The Weave developer platform exposes a REST API (base `https://api.weaveconnect.com`) for building integrations across messaging, phone and calls, contacts, scheduling and appointments, payments, digital forms, reviews, and event subscriptions, authenticated with OAuth 2.0 bearer tokens issued through Weave's OIDC provider. The public API reference is published in the Weave Developer Portal at [dp.getweave.com](https://dp.getweave.com), which requires a developer login.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/weave-hq/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/weave-hq/refs/heads/main/apis.yml)

## Tags

- Communication
- Healthcare
- VoIP
- Messaging
- SMS
- Scheduling
- Payments
- Reviews
- Dental
- Veterinary

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## APIs

### Weave Messaging API

Send and retrieve two-way SMS/text messages between a practice and its patients, review message history, pull chart-thread messages, check bulk-message quota, and manage the SMS phone numbers associated with a location. Includes the Quick Fill messaging surface used to text open-appointment offers.

- **Human URL:** [https://dp.getweave.com](https://dp.getweave.com)
- **Base URL:** `https://api.weaveconnect.com`

#### Tags

- Messaging
- SMS
- Texting

#### Properties

- [Documentation](https://dp.getweave.com)
- [API Reference](https://dp.getweave.com)
- [OpenAPI](openapi/weave-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/weave-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weave-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Weave Phone & Calls API

Access the Weave VoIP phone system - list call records and call recordings, request signed URLs to download recordings, read and tag voicemails, inspect call queues and their metrics, and list department phone numbers.

- **Human URL:** [https://dp.getweave.com](https://dp.getweave.com)
- **Base URL:** `https://api.weaveconnect.com`

#### Tags

- Phone
- VoIP
- Calls

#### Properties

- [Documentation](https://dp.getweave.com)
- [OpenAPI](openapi/weave-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/weave-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weave-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Weave Contacts API

Manage the people (patients/customers) a practice communicates with - list and search contacts, read contact info records, and block or unblock a contact from receiving messages.

- **Human URL:** [https://dp.getweave.com](https://dp.getweave.com)
- **Base URL:** `https://api.weaveconnect.com`

#### Tags

- Contacts
- Persons
- CRM

#### Properties

- [Documentation](https://dp.getweave.com)
- [OpenAPI](openapi/weave-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/weave-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weave-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Weave Scheduling & Appointments API

Read and manage appointments, appointment types, schedules, and calendar events; submit online booking requests; and pull online-scheduling reporting. Backs Weave's online scheduling and appointment-reminder features.

- **Human URL:** [https://dp.getweave.com](https://dp.getweave.com)
- **Base URL:** `https://api.weaveconnect.com`

#### Tags

- Scheduling
- Appointments
- Calendar

#### Properties

- [Documentation](https://dp.getweave.com)
- [OpenAPI](openapi/weave-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/weave-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weave-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Weave Payments API

Access Weave Payments - list a practice account's stored payment methods and finance-account payment methods that back text-to-pay, card-on-file, and in-office payment collection.

- **Human URL:** [https://dp.getweave.com](https://dp.getweave.com)
- **Base URL:** `https://api.weaveconnect.com`

#### Tags

- Payments
- Text to Pay
- Billing

#### Properties

- [Documentation](https://dp.getweave.com)
- [Terms Of Service](https://getweave.com/legal/payments/)
- [OpenAPI](openapi/weave-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/weave-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weave-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Weave Digital Forms API

Work with Weave Digital Forms - list forms and digital-form templates, generate patient-facing form links, retrieve submitted forms, and mark a form submission complete. Powers digital intake and medical-history collection.

- **Human URL:** [https://dp.getweave.com](https://dp.getweave.com)
- **Base URL:** `https://api.weaveconnect.com`

#### Tags

- Forms
- Digital Forms
- Intake

#### Properties

- [Documentation](https://dp.getweave.com)
- [OpenAPI](openapi/weave-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/weave-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weave-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Weave Reviews API

Support Weave's review-generation and reputation features - read provider review data, check review-request completion, and inspect the status of a location's online business listing.

- **Human URL:** [https://dp.getweave.com](https://dp.getweave.com)
- **Base URL:** `https://api.weaveconnect.com`

#### Tags

- Reviews
- Reputation
- Listings

#### Properties

- [Documentation](https://dp.getweave.com)
- [OpenAPI](openapi/weave-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/weave-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weave-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Weave Events & Subscriptions API

Read platform events and manage event subscriptions - subscribe or unsubscribe a client to one or many event streams (calls, messages, appointments, payments, forms) so integrations can react to activity in near real time.

- **Human URL:** [https://dp.getweave.com](https://dp.getweave.com)
- **Base URL:** `https://api.weaveconnect.com`

#### Tags

- Events
- Webhooks
- Subscriptions

#### Properties

- [Documentation](https://dp.getweave.com)
- [OpenAPI](openapi/weave-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/weave-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weave-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/getweave)
- [LinkedIn](https://www.linkedin.com/company/weavehq)
- [Website](https://www.getweave.com)
- [Documentation](https://dp.getweave.com)
- [Plans](plans/weave-hq-plans-pricing.yml)
- [Rate Limits](rate-limits/weave-hq-rate-limits.yml)
- [Fin Ops](finops/weave-hq-finops.yml)

## Authentication

The Weave API uses OAuth 2.0. Access tokens are issued by Weave's OIDC provider (issuer `https://oidc.weaveconnect.com`, token endpoints under `https://auth.weaveconnect.com/oauth2/default`) and passed as `Authorization: Bearer ACCESS_TOKEN`. Most requests are scoped to a single Weave location (sub-account).

## Notes on Grounding

The authoritative Weave API reference lives in the Weave Developer Portal ([dp.getweave.com](https://dp.getweave.com)), a single-page app gated behind a developer login. The endpoint paths and base URL captured here are grounded in that portal's own published client (its runtime configuration and the calls it makes against `https://api.weaveconnect.com`), so path coverage is high-confidence, while request/response schemas in the OpenAPI are modeled and should be reconciled against the official reference. See [review.yml](review.yml) for the WebSocket assessment.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
