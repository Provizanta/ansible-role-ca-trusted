Ansible role: Trusted CA
=========

![Build & Deploy](https://github.com/Provizanta/ansible-role-ca-trusted/workflows/molecule/badge.svg?branch=master)

Add CA certificates to the system trusted certificates.

Requirements
------------

None

Role Variables
--------------

These defaults are set in [defaults/main.yml](defaults/main.yml):

    ca_trusted_certificates: []   # add these certificates to the trusted CA certificates

Dependencies
------------

None

Example Playbook
----------------

In a minimalistic scenario no vars need to be supplied.

    - hosts: servers
      roles:
        - role: ca-trusted
          vars:
            ca_trusted_certificates:
              - "/tmp/certs/GIAG2.crt"      # from ansible host machine


License
-------

MIT

Author Information
------------------

Tibor Csóka
