# CometChat (cometchat)

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
