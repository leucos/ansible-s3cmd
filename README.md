s3cmd role
==========

s3cmd role

This role will let you s3cmd and configure it

Requirements
------------

None

Role Variables
--------------

- `s3cmd_access_key`: S3 access key
- `s3cmd_secret_key`: S3 secret key
- `s3cmd_user`: Username to deploy configuration to

Usage
-----

The role is supposed to be used this way from a playbook:

   - { role: leucos.s3cmd }

Dependencies
------------

None

License
-------

MIT

Author Information
------------------

[@leucos](https://github.com/leucos)
