solutiondrive.server
====================

Role for generell server tasks

Requirements
------------

none

Role Variables
--------------

- `timezone` timezone to set on the server (default: 'Europe/Berlin')

Dependencies
------------

role stouts.locale

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: solutiondrive.server

License
-------

BSD

Author Information
------------------

solutionDrive <info@solutiondrive.de>
