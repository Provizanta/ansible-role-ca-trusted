Trusted CA
=========

Add trusted CA.

Requirements
------------

None

Role Variables
--------------

certificates_path: path to the directory with certificates

Dependencies
------------

None

Example Playbook
----------------

In a minimalistic scenario no vars need to be supplied.

    - hosts: servers
      roles:
       - role: ca/trusted
         vars:
           certificates_path: "~/ca/

License
-------

MIT

Author Information
------------------

Tibor Csoka
