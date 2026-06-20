# Documenso (documenso)

Documenso is the open-source DocuSign alternative, a developer-friendly e-signature platform for sending, signing, and managing documents. Its public REST API lets you create and upload documents, add recipients and signature fields, send documents for signing, work with reusable templates, and receive webhook events across the document lifecycle. Self-hostable under AGPL.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/documenso/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/documenso/refs/heads/main/apis.yml)

## Tags

- E-Signature
- Documents
- Signing
- Open Source
- DocuSign Alternative

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Documenso Documents API

Create, upload, retrieve, download, send, re-send, and delete documents. Upload returns a presigned URL for the document PDF, and documents move through a DRAFT, PENDING, COMPLETED, REJECTED, or CANCELLED lifecycle.

- **Human URL:** [https://docs.documenso.com/developers/public-api](https://docs.documenso.com/developers/public-api)
- **Base URL:** `https://app.documenso.com/api/v1`

#### Tags

- Documents
- Signing
- E-Signature

#### Properties

- [Documentation](https://docs.documenso.com/developers/public-api)
- [API Reference](https://docs.documenso.com/developers/public-api/reference)
- [OpenAPI](openapi/documenso-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/documenso.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [GitHub](https://github.com/documenso/documenso)

### Documenso Recipients API

Manage the recipients of a document - create, update, and delete signers, approvers, viewers, CCs, and assistants, with configurable roles and signing order.

- **Human URL:** [https://docs.documenso.com/developers/public-api](https://docs.documenso.com/developers/public-api)
- **Base URL:** `https://app.documenso.com/api/v1`

#### Tags

- Recipients
- Signers
- Documents

#### Properties

- [Documentation](https://docs.documenso.com/developers/public-api)
- [API Reference](https://docs.documenso.com/developers/public-api/reference)
- [OpenAPI](openapi/documenso-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/documenso.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [GitHub](https://github.com/documenso/documenso)

### Documenso Fields API

Add and configure signature and form fields on a document - signatures, initials, name, email, date, text, number, radio, checkbox, and dropdown - positioned by page and percentage coordinates and bound to a recipient.

- **Human URL:** [https://docs.documenso.com/developers/public-api](https://docs.documenso.com/developers/public-api)
- **Base URL:** `https://app.documenso.com/api/v1`

#### Tags

- Fields
- Signature Fields
- Documents

#### Properties

- [Documentation](https://docs.documenso.com/developers/public-api)
- [API Reference](https://docs.documenso.com/developers/public-api/reference)
- [OpenAPI](openapi/documenso-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/documenso.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [GitHub](https://github.com/documenso/documenso)

### Documenso Templates API

Create, retrieve, and delete reusable document templates, and generate new documents from a template with overridable title, recipients, and meta options.

- **Human URL:** [https://docs.documenso.com/developers/public-api](https://docs.documenso.com/developers/public-api)
- **Base URL:** `https://app.documenso.com/api/v1`

#### Tags

- Templates
- Documents
- Automation

#### Properties

- [Documentation](https://docs.documenso.com/developers/public-api)
- [API Reference](https://docs.documenso.com/developers/public-api/reference)
- [OpenAPI](openapi/documenso-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/documenso.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [GitHub](https://github.com/documenso/documenso)

### Documenso Webhooks

Outbound webhook events covering the full document lifecycle - created, sent, opened, signed, completed, rejected, cancelled - plus template events. Payloads are verified with a shared secret sent in the X-Documenso-Secret header.

- **Human URL:** [https://docs.documenso.com/docs/developers/webhooks](https://docs.documenso.com/docs/developers/webhooks)
- **Base URL:** `https://app.documenso.com/api/v1`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.documenso.com/docs/developers/webhooks)
- [Documentation](https://docs.documenso.com/docs/developers/webhooks/verification)
- [GitHub](https://github.com/documenso/documenso)

## Common Properties

- [GitHub Organization](https://github.com/documenso)
- [LinkedIn](https://www.linkedin.com/company/documenso)
- [Website](https://documenso.com)
- [Documentation](https://docs.documenso.com)
- [Plans](plans/documenso-plans-pricing.yml)
- [Rate Limits](rate-limits/documenso-rate-limits.yml)
- [Fin Ops](finops/documenso-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
