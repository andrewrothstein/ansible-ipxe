andrewrothstein.ipxe
=========
![Build Status](https://github.com/andrewrothstein/ansible-ipxe/actions/workflows/build.yml/badge.svg)

Builds [ipxe](http://ipxe.org/) from sources.

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
    - andrewrothstein.ipxe
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
