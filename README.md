Nodejs
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
