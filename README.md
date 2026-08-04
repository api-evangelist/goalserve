# GoalServe (goalserve)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

GoalServe is a live sports data feeds provider founded in 2005, delivering live scores, fixtures, standings, odds, commentaries, and team/player data across 20+ sports and 500+ soccer leagues. Feeds are served as XML or JSON over HTTP GET with a unique API access key carried in the request path.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/goalserve/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/goalserve/refs/heads/main/apis.yml)

## Tags

- Sports Data
- Live Scores
- Odds
- Fixtures
- Soccer

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### GoalServe Live Scores API

Real-time live score feeds for in-progress soccer matches, including goals, cards, substitutions and current minute, refreshed every few seconds and delivered as XML or JSON.

- **Human URL:** [https://www.goalserve.com/en/sport-data-feeds/soccer-api/description](https://www.goalserve.com/en/sport-data-feeds/soccer-api/description)
- **Base URL:** `https://www.goalserve.com/getfeed`

#### Tags

- Live Scores
- Real Time
- Soccer

#### Properties

- [Documentation](https://documentation.goalserve.com/v1/)
- [API Reference](https://www.goalserve.com/en/api-documentation)
- [OpenAPI](openapi/goalserve-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/goalserve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/goalserve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GoalServe Fixtures and Schedules API

Upcoming match fixtures, schedules and historical results by country and competition, supporting calendar and results-page use cases.

- **Human URL:** [https://www.goalserve.com/en/sport-data-feeds/soccer-api/sample/7](https://www.goalserve.com/en/sport-data-feeds/soccer-api/sample/7)
- **Base URL:** `https://www.goalserve.com/getfeed`

#### Tags

- Fixtures
- Schedules
- Results

#### Properties

- [Documentation](https://documentation.goalserve.com/v1/)
- [OpenAPI](openapi/goalserve-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/goalserve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/goalserve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GoalServe Standings API

League and championship standings tables plus top scorers per competition, returned in XML or JSON.

- **Human URL:** [https://www.goalserve.com/en/sport-data-feeds/soccer-api/sample/6](https://www.goalserve.com/en/sport-data-feeds/soccer-api/sample/6)
- **Base URL:** `https://www.goalserve.com/getfeed`

#### Tags

- Standings
- League Tables
- Top Scorers

#### Properties

- [Documentation](https://documentation.goalserve.com/v1/)
- [OpenAPI](openapi/goalserve-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/goalserve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/goalserve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GoalServe Odds API

Prematch and in-play bookmaker odds across 100+ betting markets and 30+ bookmakers, with low-latency in-play updates gated behind IP whitelisting.

- **Human URL:** [https://www.goalserve.com/en/sport-data-feeds/soccer-api/description](https://www.goalserve.com/en/sport-data-feeds/soccer-api/description)
- **Base URL:** `https://www.goalserve.com/getfeed`

#### Tags

- Odds
- Betting
- In-Play

#### Properties

- [Documentation](https://documentation.goalserve.com/v1/)
- [OpenAPI](openapi/goalserve-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/goalserve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/goalserve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GoalServe Commentaries API

Per-match textual commentaries and detailed event tracking (goals, cards, substitutions, lineups) keyed by match identifier.

- **Human URL:** [https://www.goalserve.com/en/sport-data-feeds/soccer-api/samples](https://www.goalserve.com/en/sport-data-feeds/soccer-api/samples)
- **Base URL:** `https://www.goalserve.com/getfeed`

#### Tags

- Commentaries
- Match Events
- Play by Play

#### Properties

- [Documentation](https://documentation.goalserve.com/v1/)
- [OpenAPI](openapi/goalserve-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/goalserve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/goalserve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GoalServe Team and Player Data API

Team and player profiles, squad data, statistics and injuries keyed by team or player identifier.

- **Human URL:** [https://www.goalserve.com/en/sport-data-feeds/soccer-api/sample/8](https://www.goalserve.com/en/sport-data-feeds/soccer-api/sample/8)
- **Base URL:** `https://www.goalserve.com/getfeed`

#### Tags

- Team Data
- Player Data
- Profiles

#### Properties

- [Documentation](https://documentation.goalserve.com/v1/)
- [OpenAPI](openapi/goalserve-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/goalserve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/goalserve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/goalserve-api)
- [Website](https://www.goalserve.com)
- [Documentation](https://documentation.goalserve.com/v1/)
- [Plans](plans/goalserve-plans-pricing.yml)
- [Rate Limits](rate-limits/goalserve-rate-limits.yml)
- [Fin Ops](finops/goalserve-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
