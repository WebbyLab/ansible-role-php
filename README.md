PHP
=========

Ansible role for php (Ubuntu server).

Role Variables
--------------

    php_min_version: 5.4

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: WebbyLab.php
           php_min_version: 5.5

License
-------

MIT

Author Information
------------------

WebbyLab ( http://webbylab.com )