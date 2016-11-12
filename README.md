Ansible Role: dummy

Build status for this role: [![Build Status](https://travis-ci.org/webofmars/ansible-dummy.svg?branch=master)](https://travis-ci.org/webofmars/ansible-dummy.svg?branch=master)

This role does nothing except displaying a welcome message.
This is used to test your setup of ansible galaxy or when using a ansible galaxy requirements.yml which may complaining because it's empty.

the role is ultra slim so you won't spend too much time downloading and running.

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
