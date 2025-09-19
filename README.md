# cronic

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/cronic)
[![General Workflow](https://github.com/rolehippie/cronic/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/cronic/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/cronic/actions/workflows/docs.yml/badge.svg)](https://github.com/rolehippie/cronic/actions/workflows/docs.yml)
[![Galaxy Workflow](https://github.com/rolehippie/cronic/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/cronic/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/cronic)](https://github.com/rolehippie/cronic/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.cronic-blue)](https://galaxy.ansible.com/rolehippie/cronic)

Ansible role to install the cronic executable.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [cronic_destination](#cronic_destination)
  - [cronic_group](#cronic_group)
  - [cronic_owner](#cronic_owner)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`

## Default Variables

### cronic_destination

Destination for executable

#### Default value

```YAML
cronic_destination: /usr/bin/cronic
```

### cronic_group

Group for the executable

#### Default value

```YAML
cronic_group: root
```

### cronic_owner

User for the executable

#### Default value

```YAML
cronic_owner: root
```

## Discovered Tags

**_cronic_**

## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
