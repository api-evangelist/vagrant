# Vagrant

Vagrant, by HashiCorp, is a tool for building and managing virtualized development environments. Their developer platform provides APIs and SDKs for interacting with Vagrant Cloud and the HCP Vagrant Box Registry, enabling automation of box lifecycle management, plugin development, and integration with CI/CD pipelines.

**Human URL:** [https://developer.hashicorp.com/vagrant](https://developer.hashicorp.com/vagrant)

**Base URL:** `https://app.vagrantup.com/api/v2`

## Description

Vagrant enables developers to create and configure lightweight, reproducible, and portable development environments. The Vagrant Cloud API provides programmatic access to manage boxes, versions, and providers, while the HCP Vagrant Box Registry API offers tighter integration with the broader HashiCorp Cloud Platform.

## Links

- [Developer Portal](https://developer.hashicorp.com/vagrant)
- [Documentation](https://developer.hashicorp.com/vagrant/docs)
- [Website](https://www.vagrantup.com/)
- [GitHub](https://github.com/hashicorp/vagrant)
- [Support](https://support.hashicorp.com/)
- [Blog](https://www.hashicorp.com/blog)

## Tags

`DevOps` `Virtualization` `Development Environments` `Boxes` `Cloud` `HashiCorp` `Infrastructure`

## OpenAPI Specifications

| API | File |
|---|---|
| Vagrant Cloud API v2 | [openapi/vagrant-cloud-api-openapi.yml](openapi/vagrant-cloud-api-openapi.yml) |
| HCP Vagrant Box Registry API | [openapi/vagrant-hcp-vagrant-box-registry-openapi.yml](openapi/vagrant-hcp-vagrant-box-registry-openapi.yml) |

## JSON Schemas

| Schema | File |
|---|---|
| Vagrant Box | [json-schema/vagrant-box-schema.json](json-schema/vagrant-box-schema.json) |

## JSON Structure

| Structure | File |
|---|---|
| Vagrant Box | [json-structure/vagrant-box-structure.json](json-structure/vagrant-box-structure.json) |

## JSON-LD Context

| Context | File |
|---|---|
| Vagrant | [json-ld/vagrant-context.jsonld](json-ld/vagrant-context.jsonld) |

## Examples

| Example | File |
|---|---|
| Search Boxes | [examples/vagrant-list-boxes-example.json](examples/vagrant-list-boxes-example.json) |
| Create Box | [examples/vagrant-create-box-example.json](examples/vagrant-create-box-example.json) |

## Spectral Rules

| Ruleset | File |
|---|---|
| Vagrant Rules | [rules/vagrant-rules.yml](rules/vagrant-rules.yml) |

## Naftiko Capabilities

### Shared Definitions

| API | File |
|---|---|
| Vagrant Cloud | [capabilities/shared/vagrant-cloud.yaml](capabilities/shared/vagrant-cloud.yaml) |

### Workflow Capabilities

| Workflow | Description | File |
|---|---|---|
| Box Lifecycle | Complete box lifecycle management from discovery to publishing | [capabilities/box-lifecycle.yaml](capabilities/box-lifecycle.yaml) |

## Vocabulary

| Vocabulary | File |
|---|---|
| Vagrant | [vocabulary/vagrant-vocabulary.yml](vocabulary/vagrant-vocabulary.yml) |

## Maintainers

**Kin Lane** — [kin@apievangelist.com](mailto:kin@apievangelist.com)
