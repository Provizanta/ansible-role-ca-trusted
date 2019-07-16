Ansible role: Trusted CA
=========

[![Build Status](https://travis-ci.com/Provizanta/ansible-role-ca-trusted.svg?branch=master)](https://travis-ci.com/Provizanta/ansible-role-ca-trusted)

Add trusted CA certificates.

Requirements
------------

None

Role Variables
--------------

These defaults are set in defaults/main.yml:

    certificates_dir: "{{ ansible_user_dir }}/"   # load certificates from this dir

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
           certificates_dir: "~/ca/"

License
-------

MIT

Author Information
------------------

Tibor Csóka
