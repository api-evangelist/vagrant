# Vagrant (vagrant)

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

Vagrant, by HashiCorp, is a tool for building and managing virtualized development environments. Their developer platform provides APIs and SDKs for interacting with Vagrant Cloud and the HCP Vagrant Box Registry, enabling automation of box lifecycle management, plugin development, and integration with CI/CD pipelines.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- DevOps
- Virtualization
- Development Environments
- Boxes
- Cloud
- HashiCorp
- Infrastructure

## Timestamps

- **Created:** 2026-03-20
- **Modified:** 2026-05-19

## APIs

### Vagrant Cloud API

The Vagrant Cloud API v2 enables developers to programmatically interact with the Vagrant Cloud platform for managing Vagrant boxes, versions, and providers. It supports creating and updating boxes, publishing new versions, uploading provider binaries, and searching the public box catalog.

- **Human URL:** [https://developer.hashicorp.com/vagrant/vagrant-cloud/api/v2](https://developer.hashicorp.com/vagrant/vagrant-cloud/api/v2)
- **Base URL:** `https://app.vagrantup.com/api/v2`

#### Tags

- DevOps
- Virtualization
- Development Environments
- Boxes
- Cloud

#### Properties

- [Documentation](https://developer.hashicorp.com/vagrant/vagrant-cloud/api/v2)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/openapi/vagrant-cloud-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/rules/vagrant-rules.yml)
- [Postman Collection](collections/vagrant-cloud-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vagrant-cloud-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/vagrant-hcp-vagrant-box-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vagrant-hcp-vagrant-box-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HCP Vagrant Box Registry API

The HCP Vagrant Box Registry API provides REST endpoints for managing Vagrant box registries and boxes on the HashiCorp Cloud Platform. The API uses HCP service principal credentials for authentication and is the successor to the legacy Vagrant Cloud service.

- **Human URL:** [https://developer.hashicorp.com/hcp/api-docs/vagrant-box-registry](https://developer.hashicorp.com/hcp/api-docs/vagrant-box-registry)

#### Tags

- DevOps
- Virtualization
- Registry
- Boxes
- Cloud

#### Properties

- [Documentation](https://developer.hashicorp.com/hcp/api-docs/vagrant-box-registry)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/openapi/vagrant-hcp-vagrant-box-registry-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vagrant-cloud-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vagrant-cloud-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/vagrant-hcp-vagrant-box-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vagrant-hcp-vagrant-box-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vagrant Cloud Ruby Client

An official Ruby library that wraps the Vagrant Cloud API, providing a convenient interface for managing boxes, versions, and providers programmatically.

- **Human URL:** [https://github.com/hashicorp/vagrant_cloud](https://github.com/hashicorp/vagrant_cloud)

#### Tags

- DevOps
- Virtualization
- SDK
- Ruby
- Boxes

#### Properties

- [Documentation](https://github.com/hashicorp/vagrant_cloud)
- [SDK](https://github.com/hashicorp/vagrant_cloud)
- [Postman Collection](collections/vagrant-cloud-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vagrant-cloud-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/vagrant-hcp-vagrant-box-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vagrant-hcp-vagrant-box-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vagrant Plugin SDK

The Vagrant Plugin SDK enables developers to build plugins that extend Vagrant with custom commands, providers, provisioners, guests, and host capabilities using Go or Ruby.

- **Human URL:** [https://developer.hashicorp.com/vagrant/docs/plugins/development-basics](https://developer.hashicorp.com/vagrant/docs/plugins/development-basics)

#### Tags

- DevOps
- Virtualization
- SDK
- Plugins
- Extensibility

#### Properties

- [Documentation](https://developer.hashicorp.com/vagrant/docs/plugins/development-basics)
- [Postman Collection](collections/vagrant-cloud-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vagrant-cloud-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/vagrant-hcp-vagrant-box-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vagrant-hcp-vagrant-box-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://developer.hashicorp.com/vagrant)
- [Documentation](https://developer.hashicorp.com/vagrant/docs)
- [Website](https://www.vagrantup.com/)
- [Privacy Policy](https://www.hashicorp.com/privacy)
- [Terms of Service](https://www.hashicorp.com/terms-of-service)
- [Support](https://support.hashicorp.com/)
- [Blog](https://www.hashicorp.com/blog)
- [Login](https://app.vagrantup.com/session/new)
- [Git Hub](https://github.com/hashicorp/vagrant)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/json-schema/vagrant-box-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/json-ld/vagrant-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/rules/vagrant-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/vocabulary/vagrant-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
