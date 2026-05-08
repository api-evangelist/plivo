# Plivo (plivo)

Plivo is a global communications platform offering programmable Voice, Messaging (SMS/MMS/WhatsApp), SIP Trunking, Verify, and Lookup APIs, plus an AI Voice Agent platform.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/plivo/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=plivo-api-evangelist&utm_content=repo)

## Type

- **x-type:** company

## Tags

 - Communications, CPaaS, Voice, SMS, Messaging, WhatsApp, SIP Trunking, Verify

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

| API | Description |
|---|---|
| Plivo Account API | Account lookup and update (auth ID, balance, max-call settings) |
| Plivo Subaccount API | Multi-tenant subaccount lifecycle |
| Plivo Application API | Voice application bundles (answer/hangup/fallback URLs) |
| Plivo SIP Authentication API | Per-account SIP credentials |
| Plivo Voice Call API | Outbound calls and active-call control |
| Plivo Conference API | Live conference room management |
| Plivo Multiparty Call API | Programmatic multiparty call assembly + supervisory controls |
| Plivo Recording API | Call/conference recording retrieval |
| Plivo Endpoint API | SIP/WebRTC endpoint management |
| Plivo Audio Stream API | Real-time WebSocket audio streaming for AI agents |
| Plivo Verified Caller ID API | Verified outbound caller-ID management |
| Plivo Message API | Send/receive SMS, MMS, WhatsApp |
| Plivo Media API | MMS / WhatsApp media uploads |
| Plivo Powerpack API | Number-pool messaging traffic distribution |
| Plivo 10DLC Brand and Campaign API | A2P 10DLC compliance registration |
| Plivo Toll-Free Verification API | TFN verification cases |
| Plivo Numbers API | Search, rent, release phone numbers |
| Plivo Pricing API | Live per-country voice/SMS rate card |
| Plivo Verify API | OTP delivery and code verification |
| Plivo Lookup API | Phone-number validation, carrier, line type |
| Plivo Zentrunk SIP Trunking API | Termination + origination SIP trunks |
| Plivo CNAM Lookup and Branded Calling API | Caller-name and branded calling |

## Common Properties

- [Website](https://www.plivo.com/)
- [Documentation](https://www.plivo.com/docs/)
- [Pricing](https://www.plivo.com/pricing/)
- [GitHub Organization](https://github.com/plivo)
- [Plans](plans/plivo-plans-pricing.yml) — API Commons Plans 0.1 (reconciled)
- [RateLimits](rate-limits/plivo-rate-limits.yml) — API Commons Rate Limits 0.1 (reconciled)
- [FinOps](finops/plivo-finops.yml) — FOCUS-aligned FinOps Framework 1.0 (reconciled)

## Plans Summary

- **Free Trial** — $10 credit, no credit card
- **Pay-As-You-Go** — usage-based; e.g. US SMS long code at $0.0077/segment, US local voice from $0.0055-$0.0115/min
- **Enterprise** — starts ~$1,000/month committed spend

## Rate Limits Summary

- **REST API:** 300 requests / 5 seconds per account
- **Outbound SMS (US 10DLC):** 1 MPS per long code (carrier-driven; higher with vetted brand)
- **Outbound SMS (US Toll-Free):** 3 MPS per verified TFN
- **Concurrent voice calls:** default 100 per account (configurable)

## Artifacts

| Artifact | Path |
|---|---|
| Plans | `plans/plivo-plans-pricing.yml` |
| Rate Limits | `rate-limits/plivo-rate-limits.yml` |
| FinOps | `finops/plivo-finops.yml` |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
