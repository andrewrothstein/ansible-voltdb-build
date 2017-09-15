andrewrothstein.voltdb-build
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-voltdb-build.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-voltdb-build)

Builds [VoltDB](https://www.voltdb.com/) from source

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/mainyml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
     - andrewrothstein.voltdb-build
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
