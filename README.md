Role Name
=========
**This role is under active development**

This role provides tools necessary to manage both Linux and Windows targets for penetration testing

Requirements
------------

Ansible version 2.1 or greater

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

No current dependencies

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

     - name: Offensibe Main Playbook 
       hosts: target 
       become: true
       roles:
          - offensible

Example Execution Command
------------------

ansible-playbook playbook.yml --tags "linux,windows"
  
License
-------

BSD

Author Information
------------------

Christopher Grimm <cgrimm@redhat.com>, [Github](https://githubs.com/cgrimm-redhat)

