# Cisco Systems (cisco-systems)

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

Cisco Systems is a global technology company providing networking, security, collaboration, and cloud infrastructure products. Cisco exposes its programmable surface through Cisco DevNet, a single developer portal that aggregates documentation, sandboxes, code exchange, and learning labs across the company's hardware and software portfolio. Major API domains include Catalyst Center and Meraki for network management, IOS XE RESTCONF for device-level programmability, Webex for collaboration, Secure Firewall and ISE for security, ThousandEyes and AppDynamics for observability, and Intersight for cloud-managed infrastructure. Authentication models vary by product line and include OAuth 2.0, API keys, basic-auth token exchange, and HTTP signature authentication.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cisco-systems/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cisco-systems/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Collaboration
- Infrastructure
- Networking
- Security

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-19

## APIs

### Cisco DevNet API Catalog

Cisco DevNet is the unified developer portal for Cisco Systems products, exposing APIs, SDKs, sandboxes, and learning resources for networking, security, collaboration, and cloud infrastructure. The DevNet catalog is the entry point for discovering and authenticating against the broader Cisco API surface.

- **Human URL:** [https://developer.cisco.com/](https://developer.cisco.com/)
- **Base URL:** `https://developer.cisco.com/api`

#### Tags

- Collaboration
- DevNet
- Infrastructure
- Networking
- Security

#### Properties

- [Documentation](https://developer.cisco.com/)
- [API Reference](https://developer.cisco.com/docs/)
- [OpenAPI](openapi/cisco-systems-cisco-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-systems-cisco-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-systems-cisco-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco Catalyst Center

Cisco Catalyst Center (formerly Cisco DNA Center) provides programmable management of Cisco enterprise networks, including discovery, inventory, provisioning, and assurance.

- **Human URL:** [https://developer.cisco.com/docs/dna-center/](https://developer.cisco.com/docs/dna-center/)

#### Tags

- Catalyst
- DNA Center
- Network Management
- SDN

#### Properties

- [Documentation](https://developer.cisco.com/docs/dna-center/)
- [Postman Collection](collections/cisco-systems-cisco-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-systems-cisco-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco Meraki Dashboard

The Meraki Dashboard API exposes Cisco's cloud-managed networking hardware including switches, access points, security appliances, cameras, and sensors.

- **Human URL:** [https://developer.cisco.com/meraki/](https://developer.cisco.com/meraki/)
- **Base URL:** `https://api.meraki.com/api/v1`

#### Tags

- Cloud Managed
- Dashboard
- Wireless

#### Properties

- [Documentation](https://developer.cisco.com/meraki/api-latest/)
- [OpenAPI](https://api.meraki.com/api/v1/openapiSpec) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-systems-cisco-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-systems-cisco-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco Webex Platform

The Cisco Webex platform provides REST APIs for meetings, messaging, calling, devices, webhooks, and administrative operations across the Webex collaboration suite.

- **Human URL:** [https://developer.webex.com/](https://developer.webex.com/)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Collaboration
- Meetings
- Messaging
- Webex

#### Properties

- [Documentation](https://developer.webex.com/docs)
- [Postman Collection](collections/cisco-systems-cisco-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-systems-cisco-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco Secure Firewall Management Center

The Cisco Secure Firewall Management Center API configures ASA/FTD firewall policies, access rules, and remote-access VPN gateways across managed firewall fleets.

- **Human URL:** [https://developer.cisco.com/docs/secure-firewall-management-center-api/](https://developer.cisco.com/docs/secure-firewall-management-center-api/)

#### Tags

- Firewall
- FTD
- Security

#### Properties

- [Documentation](https://developer.cisco.com/docs/secure-firewall-management-center-api/)
- [Postman Collection](collections/cisco-systems-cisco-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-systems-cisco-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco ThousandEyes API

The Cisco ThousandEyes API provides programmatic access to digital experience, internet, and cloud network monitoring data across enterprise environments.

- **Human URL:** [https://developer.thousandeyes.com/](https://developer.thousandeyes.com/)
- **Base URL:** `https://api.thousandeyes.com/v7`

#### Tags

- Digital Experience
- Network Monitoring
- Observability

#### Properties

- [Documentation](https://developer.thousandeyes.com/v7/)
- [Postman Collection](collections/cisco-systems-cisco-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-systems-cisco-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco AppDynamics API

The Cisco AppDynamics API provides REST endpoints for application performance monitoring, business transaction analytics, and controller administration.

- **Human URL:** [https://docs.appdynamics.com/appd/24.x/latest/en/extend-cisco-appdynamics](https://docs.appdynamics.com/appd/24.x/latest/en/extend-cisco-appdynamics)

#### Tags

- APM
- Application Monitoring
- Observability

#### Properties

- [Documentation](https://docs.appdynamics.com/appd/24.x/latest/en/extend-cisco-appdynamics)
- [Postman Collection](collections/cisco-systems-cisco-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-systems-cisco-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco Intersight API

The Cisco Intersight API is a cloud-based control plane for managing Cisco UCS, HyperFlex, and partner infrastructure with OData-flavored REST endpoints.

- **Human URL:** [https://intersight.com/apidocs/](https://intersight.com/apidocs/)
- **Base URL:** `https://intersight.com/api/v1`

#### Tags

- Cloud Management
- HyperFlex
- Infrastructure
- UCS

#### Properties

- [Documentation](https://intersight.com/apidocs/introduction/overview/)
- [Postman Collection](collections/cisco-systems-cisco-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-systems-cisco-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/cisco)
- [LinkedIn](https://www.linkedin.com/company/cisco)
- [Website](https://www.cisco.com)
- [Portal](https://developer.cisco.com/)
- [Documentation](https://developer.cisco.com/docs/)
- [Sandbox](https://devnetsandbox.cisco.com/)
- [Learning](https://developer.cisco.com/learning/)
- [Code  Exchange](https://developer.cisco.com/codeexchange/)
- [Community](https://community.cisco.com/)
- [Support](https://www.cisco.com/c/en/us/support/index.html)
- [Status Page](https://status.cisco.com/)
- [Blog](https://blogs.cisco.com/)
- [Terms of Service](https://www.cisco.com/c/en/us/about/legal/cloud-and-software/end-user-license-agreement.html)
- [Privacy Policy](https://www.cisco.com/c/en/us/about/legal/privacy-full.html)
- [JSON-LD](json-ld/cisco-systems-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/cisco-systems-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
