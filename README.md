# cronic

[![Build Status](https://cloud.drone.io/api/badges/rolehippie/cronic/status.svg)](https://cloud.drone.io/rolehippie/cronic)

Ansible role to configure cronic

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

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
