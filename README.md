local_repo
=========

Create DVD repo on the target machine, useful for production machines that do not have internet access, spares the sysadmin from doing the repetitive task of configuring the dvd local repository.

Requirements
------------

The only requirement is that the installation media be inserted in the DVD drive.

Role Variables
--------------

Below are the variables that can be customized along with their default values.

local_repo_mount: /mnt/dvd
local_repo_id: DVD
local_repo_name: local repo
local_repo_enabled: 1

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
