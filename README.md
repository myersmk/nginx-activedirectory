Role Name
=========

nginx-ldap, builds nginx from source with ldap-auth module

Requirements
------------

Tested with Ansible 2.6.3

Role Variables
--------------

be sure to change defaults/main.yml to suit your domain needs
OR group_vars, to each their own

Dependencies
------------



Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: nginxldap
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

