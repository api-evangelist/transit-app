# Transit (transit-app)

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
