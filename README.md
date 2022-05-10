# Ansible Role Hostname

![Build Status](https://github.com/leadlineit/ansible-role-hostname/actions/workflows/ansible-galaxy-ci.yml/badge.svg)
[![Galaxy Role](https://img.shields.io/badge/Ansible--Galaxy-leadlineit.hostname-blue.svg?logo=ansible&logoColor=white)](https://galaxy.ansible.com/leadlineit/hostname/)

This role helps to configure or change system hostname on a Debian (stretch/buster/bullseye).

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

```yaml
---
inventory_hostname: foo.bar.com
```
You can set "inventory_hostname" variable, or it'll be pass from your ansible inventory file.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: servers
  roles:
    - { role: leadlineit.hostname, tags: hostname }
```

License
-------

BSD

Author Information
------------------

This role was created by Stas Stavnichuk.
