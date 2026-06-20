# CometChat (cometchat)

CometChat is an in-app messaging platform offering chat, voice, and video SDKs plus a server-side REST Management API. The REST API (v3) manages users, auth tokens, groups, group members, messages, conversations, reactions, roles, and webhooks for an app, while client SDKs and a managed realtime WebSocket layer deliver one-to-one and group conversations, presence, and calling.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cometchat/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cometchat/refs/heads/main/apis.yml)

## Tags

- Chat
- Messaging
- Voice
- Video
- SDK
- Realtime

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### CometChat Users API

Create, list, retrieve, update, delete, deactivate, and reactivate users, plus issue and manage per-user authentication tokens used by client SDKs to log a user into an app.

- **Human URL:** [https://www.cometchat.com/docs/rest-api/users](https://www.cometchat.com/docs/rest-api/users)
- **Base URL:** `https://{appId}.api-{region}.cometchat.io/v3`

#### Tags

- Users
- Identity
- Auth Tokens

#### Properties

- [Documentation](https://www.cometchat.com/docs/rest-api/users)
- [API Reference](https://www.cometchat.com/docs/rest-api/chat-apis)
- [OpenAPI](openapi/cometchat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cometchat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cometchat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CometChat Groups & Members API

Create, list, update, and delete public, private, and password groups, and add, list, kick, and change the scope of group members (participant, moderator, admin).

- **Human URL:** [https://www.cometchat.com/docs/rest-api/groups](https://www.cometchat.com/docs/rest-api/groups)
- **Base URL:** `https://{appId}.api-{region}.cometchat.io/v3`

#### Tags

- Groups
- Members
- Membership

#### Properties

- [Documentation](https://www.cometchat.com/docs/rest-api/groups)
- [API Reference](https://www.cometchat.com/docs/rest-api/group-members)
- [OpenAPI](openapi/cometchat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cometchat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cometchat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CometChat Messages API

Send, list, retrieve, update, and delete one-to-one and group messages, send threaded and bot messages, and add, remove, and list message reactions.

- **Human URL:** [https://www.cometchat.com/docs/rest-api/messages](https://www.cometchat.com/docs/rest-api/messages)
- **Base URL:** `https://{appId}.api-{region}.cometchat.io/v3`

#### Tags

- Messages
- Threads
- Reactions

#### Properties

- [Documentation](https://www.cometchat.com/docs/rest-api/messages)
- [API Reference](https://www.cometchat.com/docs/rest-api/messages/list-messages)
- [OpenAPI](openapi/cometchat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cometchat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cometchat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CometChat Conversations API

List and retrieve user and group conversations, update conversation metadata, and mark conversations as read, delivered, or unread for managing inbox state server-side.

- **Human URL:** [https://www.cometchat.com/docs/rest-api/conversations](https://www.cometchat.com/docs/rest-api/conversations)
- **Base URL:** `https://{appId}.api-{region}.cometchat.io/v3`

#### Tags

- Conversations
- Read Receipts
- Unread

#### Properties

- [Documentation](https://www.cometchat.com/docs/rest-api/conversations)
- [API Reference](https://www.cometchat.com/docs/rest-api/conversations/list-conversations)
- [OpenAPI](openapi/cometchat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cometchat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cometchat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CometChat Roles API

Create, list, retrieve, update, and delete custom roles that govern what users and group members can do within an app.

- **Human URL:** [https://www.cometchat.com/docs/rest-api/roles](https://www.cometchat.com/docs/rest-api/roles)
- **Base URL:** `https://{appId}.api-{region}.cometchat.io/v3`

#### Tags

- Roles
- Permissions
- Access Control

#### Properties

- [Documentation](https://www.cometchat.com/docs/rest-api/roles)
- [OpenAPI](openapi/cometchat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cometchat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cometchat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CometChat Relationships API

Manage user-to-user relationships - add, list, and remove friends; block, unblock, and list blocked users; and ban, unban, and list users banned from a group.

- **Human URL:** [https://www.cometchat.com/docs/rest-api/friends](https://www.cometchat.com/docs/rest-api/friends)
- **Base URL:** `https://{appId}.api-{region}.cometchat.io/v3`

#### Tags

- Friends
- Blocked Users
- Banned Users

#### Properties

- [Documentation](https://www.cometchat.com/docs/rest-api/friends)
- [API Reference](https://www.cometchat.com/docs/rest-api/blocked-users)
- [OpenAPI](openapi/cometchat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cometchat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cometchat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CometChat Webhooks API

Register, list, update, and delete webhooks and manage which event triggers (message sent, user created, group joined, and others) deliver callbacks to your endpoints.

- **Human URL:** [https://www.cometchat.com/docs/rest-api/management-apis/webhooks/overview](https://www.cometchat.com/docs/rest-api/management-apis/webhooks/overview)
- **Base URL:** `https://{appId}.api-{region}.cometchat.io/v3`

#### Tags

- Webhooks
- Events
- Triggers

#### Properties

- [Documentation](https://www.cometchat.com/docs/rest-api/management-apis/webhooks/overview)
- [OpenAPI](openapi/cometchat-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cometchat.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cometchat.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CometChat Realtime & Client SDK

Client SDKs (JavaScript, React, React Native, Android, iOS, Flutter, Ionic) connect over a managed WebSocket layer for realtime message delivery, typing indicators, presence, and read receipts. The socket is established and maintained by the SDK via connect()/disconnect(); CometChat does not publish a raw wss endpoint or message protocol.

- **Human URL:** [https://www.cometchat.com/docs/sdk/javascript/overview](https://www.cometchat.com/docs/sdk/javascript/overview)
- **Base URL:** `https://{appId}.api-{region}.cometchat.io/v3`

#### Tags

- Realtime
- WebSocket
- SDK
- Presence

#### Properties

- [Documentation](https://www.cometchat.com/docs/sdk/javascript/overview)
- [Documentation](https://www.cometchat.com/docs/sdk/javascript/managing-web-sockets-connections-manually)
- [AsyncAPI](asyncapi/cometchat-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

## Common Properties

- [GitHub Organization](https://github.com/cometchat)
- [LinkedIn](https://www.linkedin.com/company/cometchat)
- [Website](https://www.cometchat.com)
- [Documentation](https://www.cometchat.com/docs)
- [Plans](plans/cometchat-plans-pricing.yml)
- [Rate Limits](rate-limits/cometchat-rate-limits.yml)
- [Fin Ops](finops/cometchat-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
