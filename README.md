andrewrothstein.azurecli
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-azurecli.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-azurecli)

Installs a conda environment with azure-cli installed

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
    - andrewrothstein.azurecli
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
