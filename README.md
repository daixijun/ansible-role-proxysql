daixijun.proxysql
=========

[![Build Status](https://github.com/daixijun/ansible-role-proxysql/workflows/ci/badge.svg)](https://github.com/daixijun/ansible-role-proxysql/actions)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-daixijun.proxysql-660198.svg?style=flat)](https://galaxy.ansible.com/daixijun/proxysql/)
[![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/daixijun/ansible-role-proxysql?sort=semver)](https://github.com/daixijun/ansible-role-proxysql/tags)

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
