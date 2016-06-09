erlang
======

[![Build Status](https://travis-ci.org/kbrebanov/ansible-erlang.svg?branch=master)](https://travis-ci.org/kbrebanov/ansible-erlang)

Installs Erlang.

Requirements
------------

This role requires Ansible 1.9 or higher.

Role Variables
--------------

| Name           | Default | Description                  |
|----------------|---------|------------------------------|
| erlang_version | 18.3    | Version of Erlang to install |

Dependencies
------------

None

Example Playbook
----------------

```
- hosts: all
  roles:
    - kbrebanov.erlang
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
