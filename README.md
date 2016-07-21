ansible-cockpit
===============

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

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: galexrt.cockpit, cockpit: true }

License
-------

MIT License

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
