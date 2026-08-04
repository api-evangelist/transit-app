# Transit (transit-app)

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

Transit is a Montreal-based mobility app that provides real-time public transit, multimodal trip planning, and shared-mobility navigation across 1,000+ cities worldwide. The consumer app displays nearby buses, subways, trains, bikeshare, scooters, carshare, and on-demand transit the moment it opens, and is augmented by "GO" crowdsourced vehicle locations contributed by millions of riders. Transit operates a partner program for transit agencies, mobility operators, and third-party developers, exposing its routing, real-time, alerts, and shared-mobility surface through the public Transit API (api-doc.transitapp.com, v4 stable). The v4 API is a single OpenAPI 3.1 contract covering nearby routes and stops, stop departures, multimodal trip planning, placemarks for shared-mobility vehicles and docks, available networks, route and trip details, service alerts, and real-time vehicle positions. Authentication is an apiKey header; the free tier allows 5 requests per minute and 1,500 calls per month after key approval, with custom commercial plans available through partners@transit.app.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/transit-app/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/transit-app/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Transit
- Public Transit
- Multimodal
- Mobility
- Trip Planning
- Routing
- Real-Time
- GTFS
- GOFS
- Bikeshare
- Scooters
- Carshare
- On-Demand Transit
- Service Alerts
- Shared Mobility
- Crowdsourced Data

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Transit API

Public, real-time and trip-planning API for Transit's transit and shared-mobility data. Exposes nearby routes and stops, stop departures (schedule + real-time), multimodal trip planning, plan duration estimates, placemarks for bikeshare/scooter/carshare vehicles and docks, available sharing networks, route and trip details, service alerts, and real-time vehicle positions across 1,000+ cities. Single OpenAPI 3.1 contract under /v4/public, with map-layer endpoints for shared-mobility placemarks and networks. Auth via the apiKey header; free tier is 5 req/min and 1,500 req/month after approval.

- **Human URL:** [https://api-doc.transitapp.com/v4.html](https://api-doc.transitapp.com/v4.html)
- **Base URL:** `https://external.transitapp.com`

#### Tags

- Transit
- Public Transit
- Multimodal
- Trip Planning
- Real-Time
- Departures
- Stops
- Routes
- Service Alerts
- Shared Mobility
- Vehicle Positions
- GTFS

#### Properties

- [Documentation](https://api-doc.transitapp.com/v4.html)
- [Documentation](https://api-doc.transitapp.com/)
- [Sign Up](https://transitapp.com/apis)
- [OpenAPI](openapi/transit-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/transit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/transit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://transitapp.com)
- [Portal](https://transitapp.com)
- [A P I Portal](https://transitapp.com/apis)
- [Documentation](https://api-doc.transitapp.com/)
- [Documentation](https://api-doc.transitapp.com/v4.html)
- [Documentation](https://api-doc.transitapp.com/v3.html)
- [Partner Portal](https://resources.transitapp.com/)
- [Documentation](https://resources.transitapp.com/article/397-on-demand-transit-api-guidelines)
- [Blog](https://blog.transitapp.com/)
- [About Us](https://transitapp.com/about)
- [Vision](https://transitapp.com/vision)
- [Press](https://transitapp.com/press)
- [Help](https://help.transitapp.com/)
- [Careers](https://transitapp.com/jobs)
- [Contact](mailto:partners+website@transit.app)
- [Partners](https://transitapp.com/apis)
- [Privacy Policy](https://transitapp.com/privacy)
- [Terms of Service](https://transitapp.com/terms)
- [App Store](https://apps.apple.com/app/transit-bus-subway-times/id498151501)
- [Play Store](https://play.google.com/store/apps/details?id=com.thetransitapp.droid)
- [GitHub Organization](https://github.com/transitapp)
- [Twitter](https://twitter.com/transitapp)
- [LinkedIn](https://www.linkedin.com/company/transit-app)
- [Tool](https://github.com/transitapp/gtfs-flex-to-GOFS)
- [Tool](https://github.com/transitapp/gtfs-blocks-to-transfers)
- [Tool](https://github.com/transitapp/py-gtfs-loader)
- [Sample](https://github.com/transitapp/Transit-TV)
- [Benchmark](https://github.com/transitapp/ETA-Accuracy-Benchmark)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
