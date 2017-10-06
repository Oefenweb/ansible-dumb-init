## dump-init

[![Build Status](https://travis-ci.org/Oefenweb/ansible-dump-init.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-dump-init) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-dump--init-blue.svg)](https://galaxy.ansible.com/Oefenweb/dump-init/)

Set up (the latest or a specific version of) [dump-init](https://github.com/Yelp/dumb-init) in Debian-like systems.

#### Requirements

None

#### Variables

* `dump_init_version` [default: `v1.2.0`]: Version to install
* `dump_init_install_prefix` [default: `/usr/local/bin`]: Install prefix

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - dump-init
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-dump-init/issues)!
