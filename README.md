activate-epel
=============

This role enables EPEL in EL & CentOS 6 and 7

Requirements
------------

The system must be properly subscribed to install the required packages: yum-config-manager

Role Variables
--------------

NONE

Example Playbook
----------------

Here is an example playbook that adds two disks in volumegroup vg00 and adds another one to the existing root volumegroup

    - hosts: servers
      remote_user: root

      roles:
         - { role: mk-ansible-roles.activate-epel }

License
-------

Apache License
Version 2.0, January 2004

Author Information
------------------

Markus Koch

Please leave comments in the github repo issue list
