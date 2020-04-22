# daixijun.proxysql

[![Build Status](https://github.com/daixijun/ansible-role-proxysql/workflows/build/badge.svg)](https://github.com/daixijun/ansible-role-proxysql/actions)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-daixijun.proxysql-660198.svg?style=flat)](https://galaxy.ansible.com/daixijun/proxysql/)
[![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/daixijun/ansible-role-proxysql?sort=semver)](https://github.com/daixijun/ansible-role-proxysql/tags)

高性能 mysql 代理

## 环境要求

- RHEL/CentOS 7+
- Ansible 2.9+

## 变量

参考[defaults](./defaults/main.yml)

## 依赖

无

## 示例

```yaml
- hosts: servers
  roles:
    - { role: daixijun.proxysql, proxysql_version: 2.0.10 }
```

## License

BSD

## 维护者

- Xijun Dai <daixijun1990@gmail.com>
