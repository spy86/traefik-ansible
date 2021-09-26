Role Name
=========

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 

Role to deploy traefik binary and create systemd unit.

Requirements
------------

 - CentOS 6/7
 - Debian 
 - Ubuntu 16.04

Role Variables
--------------

None


Dependencies
------------

None

Example Playbook
----------------
```YAML
    - hosts: traefik
      roles:
         -  role: traefik
```
