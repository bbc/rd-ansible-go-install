rd-ansible-go-install  [![Build Status](https://travis-ci.org/bbc/rd-ansible-go-install.svg?branch=master)](https://travis-ci.org/bbc/rd-ansible-go-install)
=========

This role pulls down the defined version of GOLANG and installs and sets up environment variables on an Ubuntu Xenial or Bionic system.

Requirements
------------

This module requires Ansible 2.6

Role Variables
--------------

See defaults for variables and descriptions

Example Playbook
----------------

Example to call:

    - hosts: all
      roles:
         - { role: rd-ansible-go-install }
