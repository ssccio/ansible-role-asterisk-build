Role Name
=========

This is a role for building Asterisk from source on many platfoms.

Requirements
------------

The role will take care of any dependencies.

Role Variables
--------------

The asterisk user and group, by default 'asterisk'. The major version of asterisk to install, from 13 to 15, 15 being default.


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ssccio.asterisk-build, asterisk_version: 13 }

License
-------

BSD

Author Information
------------------

Ken Trenkelbach <ken@sscc.io>