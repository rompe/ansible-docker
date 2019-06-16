rompe.docker
============

This tiny role makes sure Docker is installed on CentOS.

Requirements
------------

So far this has been created for CentOS only.

Role Variables
--------------

n/a

Dependencies
------------

Needs rompe.pip to make sure PIP is available.
Needs geerlingguy.repo-epel to make sure the EPEL repository is available.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: rompe.docker, tags: "docker" }

License
-------

MIT

Author Information
------------------

Created in 2019 by Ulf Rompe
