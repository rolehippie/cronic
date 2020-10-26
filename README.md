# cronic

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/cronic) [![Build Status](https://img.shields.io/drone/build/rolehippie/cronic/master?logo=drone)](https://cloud.drone.io/rolehippie/cronic) [![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/cronic)](https://github.com/rolehippie/cronic/blob/master/LICENSE) 

Ansible role to install cronic, a cure for cron's chronic email problem 

## Sponsor 

[![Proact Deutschland GmbH](https://proact.eu/wp-content/uploads/2020/03/proact-logo.png)](https://proact.eu) 

Building and improving this Ansible role have been sponsored by my employer **Proact Deutschland GmbH**.

## Table of content

* [Default Variables](#default-variables)
  * [cronic_destination](#cronic_destination)
  * [cronic_group](#cronic_group)
  * [cronic_owner](#cronic_owner)
* [Dependencies](#dependencies)
* [License](#license)
* [Author](#author)

---

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

## Dependencies

* None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
