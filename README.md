# selinux

[![Build Status](https://travis-ci.org/m31271n/ansible-role-selinux.svg?branch=master)](https://travis-ci.org/m31271n/ansible-role-selinux)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-m31271n.selinux-blue.svg)](https://galaxy.ansible.com/m31271n/selinux)

Ansible role that controls SELinux.

## Requirements

None.

## Role Variables

+ `selinux_state` (default `disabled`)
+ `selinux_policy` (default ` `)

Read [selinux](http://docs.ansible.com/ansible/selinux_module.html) for more information.

## Dependencies

None.

## Example Playbook

```
- hosts: servers
  roles:
    - role: m31271n.selinux
      selinux_state: disabled
```

* * *

<p align="center">Made with ❤ by <a href="http://index.m31271n.com">m31271n</a></p>
