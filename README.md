wkhtmltopdf
===========

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-wkhtmltopdf.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-wkhtmltopdf)

Use this role to install the wkhtmltopdf console pdf generator + the full set of googlefonts to be used inside the generated pdf documents.

Requirements
------------

This role requires ubuntu.

Role Variables
--------------

The default set of variables can be used to define the wkhtmltopdf version to be installed

    wkhtmltopdf_patch_release: "0.12.6"
    wkhtmltopdf_full_release: "0.12.6-1"
    wkhtmltopdf_install_google_fonts: True

Example Playbook
----------------

    - hosts: wkhtmltopdf
      roles:
         - andrelohmann.wkhtmltopdf

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann
