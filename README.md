[![Build Status](https://img.shields.io/travis/quocvu/yaourt-archlinux-ansible.svg)](https://travis-ci.org/quocvu/yaourt-archlinux-ansible)
[![Ansible Role](https://img.shields.io/ansible/role/21002.svg)](https://galaxy.ansible.com/quocvu/yaourt-archlinux)


yaourt-archlinux
================

An Ansible role to install the Yaourt AUR helper on an ArchLinux host

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

To install `yaourt`, add the following in your playbook:

```
- hosts: servers
  roles:
     - { role: quocvu.yaourt-archlinux }
```

License
-------

BSD

Author Information
------------------

Quoc Vu  
https://github.com/quocvu
https://linkedin.com/in/quocvu  
