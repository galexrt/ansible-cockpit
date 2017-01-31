ansible-cockpit
===============

[![Build Status](https://travis-ci.org/galexrt/ansible-cockpit.svg?branch=master)](https://travis-ci.org/galexrt/ansible-cockpit)

An Ansible role to "setup" features of Fedora's Cockpit.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

For available variables take a look at the `defaults/main.yml`.

Dependencies
------------

None.

Example Playbook
----------------

An example playbook on how to use this role:
```
- hosts: servers
  roles:
    - { role: galexrt.cockpit, cockpit: true, cockpit-kubernetes: true }
```

License
-------

MIT

Author Information
------------------

If you have problems with the role, feel free to create an issue on Github or contact me by mail.
