## dumb-init

[![Build Status](https://travis-ci.org/Oefenweb/ansible-dumb-init.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-dumb-init) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-dumb--init-blue.svg)](https://galaxy.ansible.com/Oefenweb/dumb-init/)

Set up (the latest or a specific version of) [dumb-init](https://github.com/Yelp/dumb-init) in Debian-like systems.

#### Requirements

None

#### Variables

* `dumb_init_version` [default: `1.2.0`]: Version to install
* `dumb_init_install_prefix` [default: `/usr/local/bin`]: Install prefix

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - dumb-init
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-dumb-init/issues)!
