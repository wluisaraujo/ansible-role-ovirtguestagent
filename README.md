[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-awx.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-awx)
---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [AWX](https://github.com/ansible/awx)
------------

Description
------------

 * Ansible for oVirt Guest Agent

Requirements
------------

 *

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars:
    - name: value
  roles:
    - iac-ansible-ovirt-guest-agent
...    
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)