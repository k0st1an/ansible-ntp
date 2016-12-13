# ansible-ntp

[![Build Status](https://travis-ci.org/k0st1an/ansible-ntp.svg?branch=master)](https://travis-ci.org/k0st1an/ansible-ntp) [![Ansible Galaxy](https://img.shields.io/badge/galaxy-k0st1an.ntp-blue.svg?style=flat)](https://galaxy.ansible.com/k0st1an/ntp/)

Role for configuration NTP server.


## Project structure

    ├── defaults
    │   └── main.yml
    ├── files
    │   └── ntp.conf.orig
    ├── handlers
    │   └── main.yml
    ├── meta
    │   └── main.yml
    ├── README.md
    ├── tasks
    │   └── main.yml
    └── templates
        └── ntp.conf.j2
        └── timezone.j2


## Role Variables

`defaults/main.yml`:

```yaml
ntp_location:   "ru"
ntp_timezone:   "Europe/Moscow"
```


## License

MIT


## Author Information

  - GitHub: https://github.com/k0st1an
  - Author: Konstantin Kruglov
  - Contact: kruglovk@gmain.com
