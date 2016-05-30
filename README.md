Nodejs [![Build Status](https://travis-ci.org/SimpliField/ansible-node.svg?branch=master)](https://travis-ci.org/SimpliField/ansible-node) [![Ansible Role](https://img.shields.io/ansible/role/10027.svg?maxAge=2592000)](https://galaxy.ansible.com/SimpliField/node/)
=========

Setup nodejs

Requirements
------------

Need ansible 2+

Role Variables
--------------

```yaml
# versions available: 0.12 | 4.x | 5.x | 6.x
nodejs_version: 4.x
```

Dependencies
------------

There is no dependency.

Example Playbook
----------------

```yaml
- hosts: servers
  role:
  - { role: SimpliField.node }
```

License
-------

BSD
