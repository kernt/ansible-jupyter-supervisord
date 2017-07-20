andrewrothstein.jupyter-supervisord
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-jupyter-supervisord.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-jupyter-supervisord)

Installs a supervisord program specification for a Jupyter notebook

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
    - andrewrothstein.supervisord
    - andrewrothstein.jupyter-supervisord
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
