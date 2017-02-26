bvansomeren.freebsd-php
=======================

Installs PHP-FPM with at least one pool. By default it will pick a few changes. You can override most settings.

Requirements
------------

Tested on FreeBSD 11 within Jails. Requires pkg.

Role Variables
--------------

Way too many to list right now; Check the templates

Dependencies
------------

None

Example Playbook
----------------

This will deploy a simple php process on 127.0.0.1 port 9000 as user www

    - hosts: servers
  	   roles:
      - bvansomeren.freebsd-php

License
-------

BSD

Author Information
------------------

