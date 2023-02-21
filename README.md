andrewrothstein.lftp
=========
![Build Status](https://github.com/andrewrothstein/ansible-lftp/actions/workflows/build.yml/badge.svg)

Installs [lftp](https://lftp.yar.ru/).

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.lftp
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
