local_repo
=========

Create DVD repo on the target machine, useful for production machines that do not have internet access, spares the sysadmin from doing the repetitive task of configuring the dvd local repository.

Requirements
------------

The only requirement is that the installation media be inserted in the DVD drive.

Role Variables
--------------

The role is very simple and short, you can edit the tasks file directly.

Dependencies
------------

No dependencies needed.

Example Playbook
----------------


    - hosts: servers
      roles:
         - role: hamdighodbane.local_repo

License
-------

BSD

Author Information
------------------

Hamdi Ghodbane, email: hamdighodbane91@gmail.com.
