# Veli (veli)

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

Veli provides crypto investment strategies via API, enabling platforms to offer smart investment solutions while handling running investment strategies, buying, selling, rebalancing, and fee collection behind the scenes. Partners retain custody and execution while Veli manages the strategy logic.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/veli/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/veli/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Crypto
- DeFi
- Finance
- Investment
- Portfolio Management

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Veli API

The Veli API enables financial platforms and crypto exchanges to integrate automated investment strategies for their users. Partners keep custody and execution while Veli handles the strategy engine: portfolio creation, automated rebalancing, buy/sell execution signals, fee collection, and performance reporting. Supports index-based, theme-based, and custom strategy portfolios.

- **Human URL:** [https://veli.io/](https://veli.io/)

#### Tags

- Crypto
- DeFi
- Finance
- Investment
- Portfolio Management

#### Properties

- [Documentation](https://veli.io/)
- [Portal](https://veli.io/)
- [OpenAPI](openapi/veli-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/veli.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veli.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/veli-portfolio-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/veli-strategy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/veli-position-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/veli-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/veli-asset-allocation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/veli-performance-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/veli-create-portfolio-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/veli-portfolio-structure.json)
- [JSON Structure](json-structure/veli-strategy-structure.json)
- [JSON Structure](json-structure/veli-position-structure.json)
- [JSON Structure](json-structure/veli-order-structure.json)
- [JSON Structure](json-structure/veli-asset-allocation-structure.json)
- [JSON Structure](json-structure/veli-performance-response-structure.json)
- [JSON Structure](json-structure/veli-create-portfolio-request-structure.json)
- [Example](examples/veli-portfolio-example.json)
- [Example](examples/veli-strategy-example.json)
- [Example](examples/veli-position-example.json)
- [Example](examples/veli-order-example.json)
- [Example](examples/veli-asset-allocation-example.json)
- [Example](examples/veli-performance-response-example.json)
- [Example](examples/veli-create-portfolio-request-example.json)

## Common Properties

- [Website](https://veli.io/)
- [Portal](https://veli.io/)
- [Documentation](https://veli.io/)
- [Spectral Rules](rules/veli-spectral-rules.yml)
- [Vocabulary](vocabulary/veli-vocabulary.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
