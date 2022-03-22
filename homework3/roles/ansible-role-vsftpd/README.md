ansible-role-vsftpd
=========

This role installs and configures vsftpd service.

Role Requirements
----------------

Install role requirements with command: `ansible-galaxy collection install -r requirements.yml`.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: antonsukhanov.ansible-role-vsftpd }

License
-------

BSD-3-Clause

Author Information
------------------

Anton Sukhanov
