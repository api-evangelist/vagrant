# Vagrant (vagrant)

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
