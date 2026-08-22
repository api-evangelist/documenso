# Documenso (documenso)

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
