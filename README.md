JUMP
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

Example assumes running from tests/:

    - hosts: servers
      roles:
         - ../../tobmat.jump

License
-------

BSD

Author Information
------------------

Toby Matherly, tobmat@gmail.com
