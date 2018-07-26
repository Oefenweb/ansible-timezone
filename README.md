## timezone

[![Build Status](https://travis-ci.org/Oefenweb/ansible-timezone.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-timezone) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-timezone-blue.svg)](https://galaxy.ansible.com/Oefenweb/timezone)

Set timezone on Debian-like systems.

#### Requirements

None

#### Variables

 * `timezone_zone` [default: `Etc/UTC`]: A timezone (e.g. UTC, Europe/Amsterdam)

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - timezone
```

#### License

MIT

#### Author Information

Mischa ter Smitten (based on work of [knopki](https://github.com/knopki))

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-timezone/issues)!
