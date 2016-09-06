# Ansible Role: PHP

[![Build Status](https://travis-ci.org/chrsclmn/ansible-role-php.svg?branch=master)](https://travis-ci.org/chrsclmn/ansible-role-php)

An Ansible role that installs PHP on Ubuntu 16.04.

## Role Variables

	php_packages: []
	php_pear_packages: []

## Dependencies

- chrsclmn.apache

## Example Playbook

    - hosts: servers
      roles:
         - { role: chrsclmn.php }

## License

BSD
