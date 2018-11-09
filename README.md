bvansomeren.php
=======================

Installs PHP-FPM with at least one pool on FreeBSD.
Uses my defaults, but everything can be overridden.

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
      - bvansomeren.php

License
-------

BSD

Author Information
------------------

