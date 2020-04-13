![Ansible Lint](https://github.com/johanneskastl/ansible-role-zypper_ref_accept_keys/workflows/Ansible%20Lint/badge.svg)

zypper_ref_accept_keys
=========

Triggering a zypper refresh on SUSE/openSUSE machines and accepting all unknown GPG keys (use with caution...)

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: 'johanneskastl.zypper_ref_accept_keys' }

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
