Role for managing AWS instances
=========

This role manages AWS and mimic the behavior of ansible-role-cloud-infra

Requirements
------------

Same as the requirements for AWS modules.
- recent boto python module

Role Variables
--------------

# Which DC to use
aws_zone: null

#
...

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

