Ansible Role: dummy

Build status for this role: [![Build Status](https://travis-ci.org/webofmars/ansible-dummy.svg?branch=master)](https://travis-ci.org/webofmars/ansible-dummy.svg?branch=master)

This role installs and configures magallanes / magephp on a linux system with PHP > 5.3 running on it.

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
```
- hosts: all
  become: yes
  become_method: sudo
  roles:
    - role: webofmars.dummy
```

This will do nothing except print a welcome message

License
-------

GPLv3


Author Information
------------------

Created by Frederic Leger / webofmars.
