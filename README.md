Role Name
=========

Install Phpmyadmin

Requirements
------------

None

Role Variables
--------------

- phpmyadmin_web_dir: web installation directory (es:'/var/www/html/phpmyadmin')
- phpmyadmin_version: software version (es:"4.7.9")
Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      vars:
        phpmyadmin_web_dir: '/var/www/html/phpmyadmin'
        phpmyadmin_version: "4.7.9"   
      roles:
         - phpmyadmin

License
-------

BSD

Author Information
------------------

Antonio Barbaro <antonio.barbaro@gmail.com>
