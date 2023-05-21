CentOS Stream after install
=========

Minimal settings after installation

Requirements
------------

ssh, python39 (or python311), pip

Role Variables
--------------


Dependencies
------------


Example Playbook
----------------

    - hosts: servers
      roles:
         - user-create
         - ssh-prepare
         - packages-install

Author Information
------------------

nudimannui4e.github.io
