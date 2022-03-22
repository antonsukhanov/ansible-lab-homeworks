ansible-role-httpd
=========

This role installs and configures httpd service.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: antonsukhanov.ansible-role-httpd, apache_default_page_heading: Welcome to my new web servers }

License
-------

BSD-3-Clause

Author Information
------------------

Anton Sukhanov
