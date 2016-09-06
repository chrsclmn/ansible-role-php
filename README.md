Ansible Role: PHP
=========

An Ansible role that installs PHP on Ubuntu 16.04.

Role Variables
--------------

	php_packages: []
	php_pear_packages: []

Dependencies
------------

 * chrsclmn.apache

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: webservers
      roles:
         - { role: chrsclmn.php }

License
-------

BSD
