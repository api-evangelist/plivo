# Plivo (plivo)

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

Plivo is a global communications platform offering programmable Voice, Messaging (SMS/MMS/WhatsApp), SIP Trunking, Verify, and Lookup APIs, plus an AI Voice Agent platform. The HTTP API is available at https://api.plivo.com/v1/ with HTTP Basic Auth using Auth ID and Auth Token credentials.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/plivo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/plivo/refs/heads/main/apis.yml)

## Tags

- Communications
- CPaaS
- Voice
- SMS
- Messaging
- WhatsApp
- SIP Trunking
- Verify

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-29

## APIs

### Plivo Account API

The Plivo Account API exposes account-level details (auth ID, auth token, billing balance, address, account type, max-call configuration) and supports updating account properties.

#### Tags

- Account
- Authentication

#### Properties

- [Documentation](https://www.plivo.com/docs/account/api/account/)
- [API Reference](https://www.plivo.com/docs/account/api/)
- [Postman Collection](collections/plivo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plivo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plivo Subaccount API

The Plivo Subaccount API supports creating, updating, listing, activating, and deleting subaccounts under a parent Plivo account, enabling multi-tenant isolation of usage and billing.

#### Tags

- Subaccounts
- Multi-Tenant

#### Properties

- [Documentation](https://www.plivo.com/docs/account/api/subaccount/)
- [Postman Collection](collections/plivo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plivo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plivo Application API

The Plivo Application API manages voice applications — bundles of XML/answer/hangup/fallback URLs (and message URL bindings) used to control inbound and outbound call behavior.

#### Tags

- Applications
- Voice
- Webhooks

#### Properties

- [Documentation](https://www.plivo.com/docs/account/api/application/)
- [Postman Collection](collections/plivo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plivo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plivo SIP Authentication API

The Plivo SIP Authentication API issues per-account credentials used by SIP endpoints to register against Plivo's SIP infrastructure.

#### Tags

- SIP
- Authentication
- Endpoints

#### Properties

- [Documentation](https://www.plivo.com/docs/account/api/sip-auth/)
- [Postman Collection](collections/plivo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plivo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plivo Voice Call API

The Plivo Voice Call API initiates outbound calls, retrieves details for live and historical calls, and supports active-call control (transfer, record, play, speak, hangup, DTMF send) on in-progress calls.

#### Tags

- Voice
- Calls
- Outbound
- Inbound

#### Properties

- [Documentation](https://www.plivo.com/docs/voice/api/call/)
- [API Reference](https://www.plivo.com/docs/voice/api/)
- [Postman Collection](collections/plivo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plivo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plivo Conference API

The Plivo Conference API manages live conference rooms — listing, retrieving members, kicking, muting, deafening, recording, and playing media into a conference.

#### Tags

- Voice
- Conferences

#### Properties

- [Documentation](https://www.plivo.com/docs/voice/api/conference/)
- [Postman Collection](collections/plivo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plivo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plivo Multiparty Call API

The Plivo Multiparty Call API supports building multi-participant calls programmatically — adding/removing participants, managing roles, recording, and barge/whisper supervisory actions.

#### Tags

- Voice
- Multiparty

#### Properties

- [Documentation](https://www.plivo.com/docs/voice/api/multipartycall/)
- [Postman Collection](collections/plivo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plivo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plivo Recording API

The Plivo Recording API exposes call and conference recordings — listing, retrieving, downloading, and deleting recorded media.

#### Tags

- Voice
- Recordings
- Media

#### Properties

- [Documentation](https://www.plivo.com/docs/voice/api/recording/)
- [Postman Collection](collections/plivo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plivo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plivo Endpoint API

The Plivo Endpoint API manages SIP/WebRTC endpoints (username/password/alias) used by softphones, browser SDKs, and devices to register and place/receive calls.

#### Tags

- SIP
- Endpoints
- WebRTC

#### Properties

- [Documentation](https://www.plivo.com/docs/voice/api/endpoint/)
- [Postman Collection](collections/plivo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plivo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plivo Audio Stream API

The Plivo Audio Stream API attaches a real-time WebSocket audio stream to a live call, enabling AI voice agents, real-time transcription, and analytics. Plivo opens a WSS connection to a customer-operated endpoint declared in the `<Stream>` XML element and exchanges JSON events (start, media, dtmf, playedStream, clearedAudio in; playAudio, checkpoint, clearAudio, sendDTMF out) following the documented Stream Event Protocol.

#### Tags

- Voice
- Streaming
- WebSocket
- AI

#### Properties

- [Documentation](https://www.plivo.com/docs/voice/api/audiostream/)
- [Documentation](https://www.plivo.com/docs/voice/xml/audiostream)
- [Documentation](https://www.plivo.com/docs/voice-agents/audio-streaming/concepts/stream-event-protocol)
- [AsyncAPI](asyncapi/plivo-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/plivo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plivo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plivo Verified Caller ID API

The Plivo Verified Caller ID API allows trial accounts to verify outbound caller IDs for use as the From number in outbound calls.

#### Tags

- Voice
- Caller ID
- Verification

#### Properties

- [Documentation](https://www.plivo.com/docs/voice/api/verified-caller-id/)
- [Postman Collection](collections/plivo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plivo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plivo Message API

The Plivo Message API sends and receives SMS, MMS, and WhatsApp messages, retrieves delivery status reports, and lists historical messages.

#### Tags

- SMS
- MMS
- WhatsApp
- Messaging

#### Properties

- [Documentation](https://www.plivo.com/docs/messaging/api/message/)
- [API Reference](https://www.plivo.com/docs/messaging/api/)
- [Postman Collection](collections/plivo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plivo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plivo Media API

The Plivo Media API uploads, lists, retrieves, and deletes media files used as MMS or WhatsApp attachments.

#### Tags

- MMS
- Media
- Uploads

#### Properties

- [Documentation](https://www.plivo.com/docs/messaging/api/media/)
- [Postman Collection](collections/plivo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plivo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plivo Powerpack API

The Plivo Powerpack API creates and manages Powerpacks — pools of numbers that distribute outbound messaging traffic for higher throughput, sticky-sender behavior, and improved deliverability.

#### Tags

- Messaging
- Number Pool
- Throughput

#### Properties

- [Documentation](https://www.plivo.com/docs/messaging/api/powerpack/)
- [Postman Collection](collections/plivo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plivo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plivo 10DLC Brand and Campaign API

The Plivo 10DLC API registers brands and campaigns with The Campaign Registry for US application-to-person (A2P) SMS compliance.

#### Tags

- 10DLC
- A2P
- Compliance
- Brand
- Campaign

#### Properties

- [Documentation](https://www.plivo.com/docs/messaging/api/10dlc/)
- [Postman Collection](collections/plivo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plivo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plivo Toll-Free Verification API

The Plivo Toll-Free Verification API submits and tracks toll-free messaging verification cases required for sustained throughput on TFNs.

#### Tags

- Toll-Free
- Compliance
- Verification

#### Properties

- [Documentation](https://www.plivo.com/docs/messaging/api/toll-free-verification/)
- [Postman Collection](collections/plivo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plivo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plivo Numbers API

The Plivo Numbers API searches the global number inventory, rents and releases phone numbers (long codes, toll-free, short codes, mobile numbers), and manages number application bindings.

#### Tags

- Phone Numbers
- Provisioning
- DIDs

#### Properties

- [Documentation](https://www.plivo.com/docs/numbers/api/)
- [Postman Collection](collections/plivo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plivo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plivo Pricing API

The Plivo Pricing API retrieves current voice and messaging rates per ISO country code, supporting cost estimation and rate-card synchronization for downstream billing.

#### Tags

- Pricing
- Rates

#### Properties

- [Documentation](https://www.plivo.com/docs/account/api/pricing/)
- [Postman Collection](collections/plivo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plivo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plivo Verify API

The Plivo Verify API delivers OTPs over SMS, voice, WhatsApp, or email and verifies user-supplied codes, supporting 2FA and identity-confirmation flows.

#### Tags

- Verify
- OTP
- 2FA
- Authentication

#### Properties

- [Documentation](https://www.plivo.com/docs/verify/api/)
- [Postman Collection](collections/plivo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plivo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plivo Lookup API

The Plivo Lookup API validates phone numbers and returns formatting, country, line type, carrier, and reachability metadata to feed cleansing, fraud-prevention, and routing decisions.

#### Tags

- Lookup
- Number Validation
- HLR
- Carrier

#### Properties

- [Documentation](https://www.plivo.com/docs/lookup/api/)
- [Postman Collection](collections/plivo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plivo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plivo Zentrunk SIP Trunking API

The Plivo Zentrunk SIP Trunking API manages termination and origination SIP trunks — outbound trunks (credentials, IP ACLs, dial prefixes) and origination/inbound trunks (URI, source IPs, recording).

#### Tags

- SIP
- Trunking
- Voice

#### Properties

- [Documentation](https://www.plivo.com/docs/sip-trunking/api/)
- [Postman Collection](collections/plivo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plivo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Plivo CNAM Lookup and Branded Calling API

The Plivo CNAM and Branded Calling API manages caller-name lookup and branded outbound caller-display configurations on outbound voice calls.

#### Tags

- CNAM
- Caller ID
- Branded Calling

#### Properties

- [Documentation](https://www.plivo.com/docs/cnam/api/)
- [Postman Collection](collections/plivo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/plivo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/plivo-inc)
- [Website](https://www.plivo.com/)
- [Documentation](https://www.plivo.com/docs/)
- [API Reference](https://www.plivo.com/docs/sms/api/)
- [Getting Started](https://www.plivo.com/docs/getting-started/)
- [Authentication](https://www.plivo.com/docs/account/api/account/)
- [Pricing](https://www.plivo.com/pricing/)
- [S D Ks](https://www.plivo.com/docs/sdks/)
- [Status Page](https://status.plivo.com/)
- [Sign Up](https://console.plivo.com/accounts/register/)
- [Login](https://console.plivo.com/)
- [GitHub Organization](https://github.com/plivo)
- [Node.js  S D K](https://github.com/plivo/plivo-node)
- [Python  S D K](https://github.com/plivo/plivo-python)
- [P H P  S D K](https://github.com/plivo/plivo-php)
- [Ruby  S D K](https://github.com/plivo/plivo-ruby)
- [Java  S D K](https://github.com/plivo/plivo-java)
- [Go  S D K](https://github.com/plivo/plivo-go)
- [. N E T  S D K](https://github.com/plivo/plivo-dotnet)
- [Browser  S D K](https://www.plivo.com/docs/sdk/web/)
- [i O S  S D K](https://www.plivo.com/docs/sdk/ios/)
- [Android  S D K](https://www.plivo.com/docs/sdk/android/)
- [Blog](https://www.plivo.com/blog/)
- [Changelog](https://www.plivo.com/changelog/)
- [X ( Twitter)](https://x.com/plivo)
- [YouTube](https://www.youtube.com/c/Plivo)
- [Plans](plans/plivo-plans-pricing.yml)
- [Rate Limits](rate-limits/plivo-rate-limits.yml)
- [Fin Ops](finops/plivo-finops.yml)
- [M C P Server](https://github.com/plivo/mcp)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
