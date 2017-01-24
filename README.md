ara_install
=========

This module installs the ARA Ansible deployment logger, along with the required web service

Requirements
------------

This module requires Ansible 2.x

Role Variables
--------------

See defaults for variables and descriptions

Dependencies
------------

This role depends on the mysql role

Example Playbook
----------------

Example to call:

    - hosts: all
      roles:
         - { role: ara_install }
