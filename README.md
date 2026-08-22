# HiveMQ (hivemq)

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

HiveMQ is an enterprise MQTT broker and IoT connectivity platform that provides reliable, scalable bidirectional messaging between connected devices and back-end systems using the MQTT protocol. It supports MQTT 3, MQTT 5, MQTT over WebSocket, clustering, multi-cloud deployments, and an extensible enterprise extension framework for security, data routing, and stream processing through HiveMQ Data Hub. HiveMQ exposes a REST API (OpenAPI 3.0) for broker administration, client management, backups, trace recordings, and Data Hub policy management.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hivemq/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hivemq/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- MQTT
- IoT
- Messaging
- Message Broker
- Pub Sub
- WebSocket

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-29

## APIs

### HiveMQ REST API

REST API for administering a HiveMQ broker including client listing and disconnection, session invalidation, backup and restore, diagnostic archive generation, trace recordings, and Data Hub schema and policy management. The API binds to 127.0.0.1:8888 by default and is documented via an OpenAPI 3.0 specification served at the /rest-api/specification/ endpoint. Authentication is configured via the HiveMQ Enterprise Security Extension or Enterprise Extension SDK REST Service.

- **Human URL:** [https://docs.hivemq.com/hivemq/latest/rest-api/index.html](https://docs.hivemq.com/hivemq/latest/rest-api/index.html)
- **Base URL:** `http://127.0.0.1:8888`

#### Tags

- Broker Administration
- Client Management
- Backup
- Data Hub
- Trace Recordings

#### Properties

- [Documentation](https://docs.hivemq.com/hivemq/latest/rest-api/index.html)
- [OpenAPI](https://docs.hivemq.com/hivemq/latest/rest-api/specification/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Configuration](https://docs.hivemq.com/hivemq/latest/rest-api/configuration.html)
- [Postman Collection](collections/hivemq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hivemq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HiveMQ MQTT over WebSocket

MQTT 3.x and MQTT 5 messaging endpoints exposed over WebSocket for browser and edge clients to publish and subscribe to topics. Used by web dashboards and JavaScript IoT clients to interact with the HiveMQ broker without native TCP MQTT support.

- **Human URL:** [https://docs.hivemq.com/hivemq/latest/user-guide/listeners.html](https://docs.hivemq.com/hivemq/latest/user-guide/listeners.html)
- **Base URL:** `ws://localhost:8000/mqtt`

#### Tags

- MQTT
- WebSocket
- Pub Sub
- IoT

#### Properties

- [Documentation](https://docs.hivemq.com/hivemq/latest/user-guide/listeners.html)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/hivemq/refs/heads/main/asyncapi/hivemq-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/hivemq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hivemq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.hivemq.com)
- [Documentation](https://docs.hivemq.com)
- [Pricing](https://www.hivemq.com/pricing)
- [Sign Up](https://www.hivemq.com/signup)
- [Cloud](https://www.hivemq.com/cloud)
- [Git Hub](https://github.com/hivemq)
- [Community  Edition](https://www.hivemq.com/developers/community)
- [Blog](https://www.hivemq.com/blog)
- [LinkedIn](https://www.linkedin.com/company/hivemq)
- [L L Ms Txt](https://docs.hivemq.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
