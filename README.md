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


Role Variables
--------------

`defaults/main.yml`:

```yaml
ntp_servers:
  - 0.ru.pool.ntp.org
	- 1.ru.pool.ntp.org
	- 2.ru.pool.ntp.org
	- 3.ru.pool.ntp.org
```


License
-------

MIT


Author Information
------------------

  - GitHub: https://github.com/k0st1an
  - Author: Konstantin Kruglov
  - Contact: kruglovk@gmain.com
