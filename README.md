PHP Redis
=========
Download and compile the redis extension for PHP 7.

Requirements
------------
PHP must already be installed.

Role Variables
--------------
    php_redis_version: 4.2.0
    
The redis extension version to download and install.    
    
Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: irmoobear.php_redis, php_redis_version: 4.2.0 }

License
-------
BSD

Author Information
------------------
An optional section for the role authors to include contact information, or a website (HTML is not allowed).