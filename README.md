wkhtmltopdf
===========

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-wkhtmltopdf.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-wkhtmltopdf)

Use this role to install the wkhtmltopdf console pdf generator + the full set of googlefonts to be used inside the generated pdf documents.

Requirements
------------

This role requires ubuntu.

Example Playbook
----------------

    - hosts: wkhtmltopdf
      roles:
         - { role: andrelohmann.ansible-role-wkhtmltopdf }

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann
