ProxySQL
=========

高性能mysql代理

Requirements
------------

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
      - { role: daixijun.proxysql, proxysql_version: 2.0.10 }
```

License
-------

BSD

Author Information
------------------

Xijun Dai <daixijun1990@gmail.com>
