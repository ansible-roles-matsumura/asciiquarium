[![](https://github.com/ansible-roles-matsumura/asciiquarium/workflows/Build/badge.svg)](https://github.com/ansible-roles-matsumura/asciiquarium/actions)

Role Name
=========

Install [ASCIIQuarium](https://robobunny.com/projects/asciiquarium/html/) for CentOS7.

Requirements
------------

EPEL installed before running this role.

Role Variables
--------------

It is recommended that all variables should not be changed.

```YAML
asciiquarium_download_url: http://www.robobunny.com/projects/asciiquarium/asciiquarium.tar.gz
asciiquarium_dir: asciiquarium_1.1
work_dir: /tmp/asciiquarium
```

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - geerlingguy.repo-epel
    - asciiquarium
```

License
-------

BSD