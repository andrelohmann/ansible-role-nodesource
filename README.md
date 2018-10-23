node.js
=======

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-nodesource.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-nodesource)

Use this role to install nodejs from the nodesource repository on your debian or ubuntu server.

Requirements
------------

This role requires debian or ubuntu.

Role Variables
--------------

The default set of variables defines the node version and needs at best to be overwritten in group_vars/host_vars

    nodesource_nodejs_version: '8'

Example Playbook
----------------

    - hosts: nodejs
      roles:
         - { role: andrelohmann.nodesource }

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann
