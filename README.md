Role Name
=========

Manages Linux pam.d configuration. Very simple role to manage our needs. Easy to customize later on.

Requirements
------------

Teste with Ansible 1.9.4

Role Variables
--------------

```
# enable sssd in pam (default value given)
pam_use_sssd: False
```

Dependencies
------------

This role is written to be standalone.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-pam }

License
-------

Apache License
Version 2.0, January 2004


Author Information
------------------
https://github.com/mhakala
