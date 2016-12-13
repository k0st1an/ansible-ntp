ansible-ntp
===========

Role for configuration NTP server.


Tested
------

  - Debian Jessie
  - Ansible 1.9.1


Project structure
-----------------

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


Role Variables
--------------

`defaults/main.yml`:

```yaml
ntp_location:   "ru"
ntp_timezone:   "Europe/Moscow"
```


License
-------

MIT


Author Information
------------------

  - GitHub: https://github.com/k0st1an
  - Author: Konstantin Kruglov
  - Contact: kruglovk@gmain.com
