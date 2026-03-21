# Vagrant (vagrant)
Vagrant, by HashiCorp, is a tool for building and managing virtualized development environments. Their developer platform provides APIs and SDKs for interacting with Vagrant Cloud and the HCP Vagrant Box Registry, enabling automation of box lifecycle management, plugin development, and integration with CI/CD pipelines.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/vagrant/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - DevOps, Virtualization, Development Environments, Boxes, Cloud

## Timestamps

- **Created:** 2026-03-20
- **Modified:** 2026-03-20

## APIs

### Vagrant Cloud API
The Vagrant Cloud API v2 enables developers to programmatically interact with the Vagrant Cloud platform for managing Vagrant boxes, versions, and providers. It supports creating and updating boxes, publishing new versions, uploading provider binaries, and searching the public box catalog. The API uses token-based authentication and is designed for automating box lifecycle management and integrating Vagrant Cloud into CI/CD pipelines.

**Human URL:** [https://developer.hashicorp.com/vagrant/vagrant-cloud/api/v2](https://developer.hashicorp.com/vagrant/vagrant-cloud/api/v2)


#### Tags:

 - DevOps, Virtualization, Development Environments, Boxes, Cloud

#### Properties

- [Documentation](https://developer.hashicorp.com/vagrant/vagrant-cloud/api/v2)
- [OpenAPI](openapi/vagrant-cloud-api-openapi.yml)

### HCP Vagrant Box Registry API
The HCP Vagrant Box Registry API provides REST endpoints for managing Vagrant box registries and boxes on the HashiCorp Cloud Platform. It supports creating and managing registries, listing and deleting boxes, and handling box versions and providers. The API uses HCP service principal credentials for authentication and is the successor to the legacy Vagrant Cloud service, offering tighter integration with the broader HashiCorp Cloud Platform ecosystem.

**Human URL:** [https://developer.hashicorp.com/hcp/api-docs/vagrant-box-registry](https://developer.hashicorp.com/hcp/api-docs/vagrant-box-registry)


#### Tags:

 - DevOps, Virtualization, Registry, Boxes, Cloud

#### Properties

- [Documentation](https://developer.hashicorp.com/hcp/api-docs/vagrant-box-registry)
- [OpenAPI](openapi/vagrant-hcp-vagrant-box-registry-openapi.yml)

### Vagrant Cloud Ruby Client
The Vagrant Cloud Ruby Client is an official Ruby library that wraps the Vagrant Cloud API, providing a convenient interface for managing boxes, versions, and providers programmatically. It allows developers to create, modify, and delete Vagrant Cloud resources from Ruby applications and scripts. The library is distributed as a RubyGem and is commonly used in automation workflows for publishing and maintaining Vagrant boxes.

**Human URL:** [https://github.com/hashicorp/vagrant_cloud](https://github.com/hashicorp/vagrant_cloud)


#### Tags:

 - DevOps, Virtualization, SDK, Ruby, Boxes

#### Properties

- [Documentation](https://github.com/hashicorp/vagrant_cloud)

### Vagrant Plugin SDK
The Vagrant Plugin SDK enables developers to build plugins that extend Vagrant with custom commands, providers, provisioners, guests, and host capabilities. Plugins are separate binaries that communicate with the Vagrant application using gRPC, and developers can use either Go or Ruby to build them. The SDK provides the foundation for adding support for new virtualization platforms, configuration management tools, and custom workflow commands to Vagrant.

**Human URL:** [https://developer.hashicorp.com/vagrant/docs/plugins/development-basics](https://developer.hashicorp.com/vagrant/docs/plugins/development-basics)


#### Tags:

 - DevOps, Virtualization, SDK, Plugins, Extensibility

#### Properties

- [Documentation](https://developer.hashicorp.com/vagrant/docs/plugins/development-basics)

## Common Properties

- [Portal](https://developer.hashicorp.com/vagrant)
- [Documentation](https://developer.hashicorp.com/vagrant/docs)
- [Website](https://www.vagrantup.com/)
- [PrivacyPolicy](https://www.hashicorp.com/privacy)
- [TermsOfService](https://www.hashicorp.com/terms-of-service)
- [Support](https://support.hashicorp.com/)
- [Blog](https://www.hashicorp.com/blog)
- [Login](https://app.vagrantup.com/session/new)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
