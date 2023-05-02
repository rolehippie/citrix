# citrix

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&amp;logoColor=white)](https://github.com/rolehippie/citrix)
[![General Workflow](https://github.com/rolehippie/citrix/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/citrix/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/citrix/actions/workflows/readme.yml/badge.svg)](https://github.com/rolehippie/citrix/actions/workflows/readme.yml)
[![Galaxy Workflow](https://github.com/rolehippie/citrix/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/citrix/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/citrix)](https://github.com/rolehippie/citrix/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.citrix-blue)](https://galaxy.ansible.com/rolehippie/citrix)

Ansible role to install citrix workspace.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [citrix_arch](#citrix_arch)
  - [citrix_package](#citrix_package)
  - [citrix_version](#citrix_version)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`


## Default Variables

### citrix_arch

Architecture for the package

#### Default value

```YAML
citrix_arch: amd64
```

### citrix_package

Download URL for the package to install

#### Default value

```YAML
citrix_package: https://dl.webhippie.de/misc/citrix-workspace_{{ citrix_version }}_{{
  citrix_arch }}.deb
```

### citrix_version

Version for the package

#### Default value

```YAML
citrix_version: 23.3.0.32
```

## Discovered Tags

**_citrix_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
