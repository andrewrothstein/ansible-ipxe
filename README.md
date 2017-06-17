andrewrothstein.ipxe
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-ipxe.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-ipxe)

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
