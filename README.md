# Resy (resy)

Resy is a restaurant reservation and discovery platform owned by American Express. Resy does not maintain a publicly self-serve developer portal; integration is restricted to approved partners (POS, CRM, loyalty, marketing, and discovery) under direct partnership agreements. The primary public surface is the consumer web and mobile app and an embeddable "Book with Resy" booking widget for restaurants. The unofficial internal client API at api.resy.com has been widely reverse-engineered by the community, but it is undocumented, unsupported, and may change without notice.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/resy/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Hospitality, Reservations, Restaurants, Dining, Booking

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-06-03

## APIs

### Resy Partner API
Partner-only REST API for reservations, availability, and restaurant metadata. Access is granted through Resy's partnerships team for approved POS, CRM, loyalty, and discovery integrations. No public developer portal or self-serve signup; no public OpenAPI specification is published.

**Human URL:** [https://resy.com/join/integrations/](https://resy.com/join/integrations/)

#### Tags:

 - REST, Partner, Reservations

#### Properties

- [Partners](https://resy.com/join/integrations/)
- [Contact](mailto:api@resy.com)

### Resy Booking Widget
Embeddable "Book with Resy" booking button/widget that restaurants and partners can place on their own websites to drive reservations into Resy. This is the primary publicly available integration surface; it is a hosted widget rather than a documented programmatic API.

**Human URL:** [https://resy.com/join/integrations/](https://resy.com/join/integrations/)

#### Tags:

 - Widget, Embed, Reservations

#### Properties

- [Documentation — Booking Button Installation](https://helpdesk.resy.com/en_us/booking-button-installation-Skx_7ueNo)

### Resy Internal Web/Mobile API (Undocumented)
Resy's web and mobile clients communicate with an internal API at api.resy.com. This API is not publicly documented or supported, requires credentials extracted from a logged-in session, and is subject to change without notice. The community has reverse-engineered it; the libraries referenced below are unofficial and not affiliated with or endorsed by Resy.

**Human URL:** [https://resy.com/](https://resy.com/)

#### Tags:

 - Internal, Undocumented, Mobile

#### Properties

- [CodeExamples — resy-cli (Community, Unofficial - Go)](https://github.com/lgrees/resy-cli)
- [CodeExamples — resy-bot (Community, Unofficial - Python)](https://github.com/jeffknaide/resy-bot)
- [CodeExamples — resy-booking-bot (Community, Unofficial - Scala)](https://github.com/Alkaar/resy-booking-bot)

## Common Properties

- [Portal](https://resy.com/)
- [Blog](https://blog.resy.com/)
- [Partners](https://resy.com/join/integrations/)
- [Contact](mailto:api@resy.com)
- [GitHubOrganization](https://github.com/resy)
- [LinkedIn](https://www.linkedin.com/company/resy-inc)
- [Plans](plans/resy-plans-pricing.yml) — restaurant SaaS + per-cover; partner API contractual (reconciled: false)
- [RateLimits](rate-limits/resy-rate-limits.yml) — per partner agreement (reconciled: false)
- [FinOps](finops/resy-finops.yml) — FOCUS-aligned hybrid (reconciled: false)

## Features

| Name | Description |
|------|-------------|
| Reservation Management | Online table reservations, waitlists, and notify lists for diners and restaurants. |
| Restaurant Discovery | Editorial dining guides, curated lists (e.g. the Resy 100), and search across cities. |
| Resy OS | Restaurant-facing operating system for table, guest, and reservation management. |
| Booking Widget | Embeddable "Book with Resy" button restaurants place on their own sites. |
| Guest CRM and Notifications | Guestbook, guest communications, and reservation notifications. |

## Use Cases

| Name | Description |
|------|-------------|
| Embed Reservations on a Restaurant Site | Add the "Book with Resy" booking button to a restaurant website to capture bookings. |
| Sync Reservations with POS and CRM | Approved partners synchronize reservation, guest, and reporting data with POS/CRM systems. |
| Discovery and Marketing Distribution | Surface restaurant availability through Resy and partner discovery channels. |

## Integrations

| Name | Description |
|------|-------------|
| POS Systems | Toast, Square, Lightspeed, Aloha, Micros Simphony, Micros 3700, Heartland Xpient, Positouch, Squirrel, Lavu, Maitre D. |
| Events and Bookings | Tripleseat for private events and group bookings. |
| CRM and Guest Management | Loyalist, Fishbowl CRM, Bloom Intelligence. |
| Discovery and Distribution | Reserve with Google, MICHELIN, The Infatuation, Meta, Anthropic, Wine Enthusiast. |
| Analytics | Google Analytics. |
| Winery and eCommerce | WineDirect, Commerce7. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
