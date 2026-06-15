# HiveMQ (hivemq)

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
