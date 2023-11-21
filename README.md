## dumb-init

[![CI](https://github.com/Oefenweb/ansible-dumb-init/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-dumb-init/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-dumb--init-blue.svg)](https://galaxy.ansible.com/Oefenweb/dumb_init/)

Set up (the latest or a specific version of) [dumb-init](https://github.com/Yelp/dumb-init) in Debian-like systems.

#### Requirements

None

#### Variables

* `dumb_init_version` [default: `1.2.5`]: Version to install
* `dumb_init_install_prefix` [default: `/usr/local/bin`]: Install prefix

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - oefenweb.dumb-init
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-dumb-init/issues)!
