Role Name
=========

This is a basic role that has the setup needed to run ansible through a jump / bastion hosts.

Requirements
------------

To test this role you need to update the tests/inventory and tests/ssh_config files.  Instructions are in the comments of tests/ssh_config.

Role Variables
--------------

None

Dependencies
------------

None

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

Toby Matherly, tobmat@gmail.com
