Ansible Role: APT Source
=========

Change Ubuntu APT source repo.

Requirements
------------

None.

Role Variables
--------------

`apt_source`: The apt source reop. (Default: `http://archive.ubuntu.com/ubuntu/`)

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: all
  become: yes
  vars:
    apt_source: http://mirrors.aliyun.com/ubuntu/
  roles:
    - { djx339.apt-source }
```

License
-------

BSD

Author Information
------------------

This role was created by [Daniel D](https://github.com/djx339).
