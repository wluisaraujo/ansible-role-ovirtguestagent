[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-oVirt%20SGuestAgent-blue.svg)](https://galaxy.ansible.com/wluisaraujo/ansible_ovirt_guest_agent) [![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-ovirt-guest-agent.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-ovirt-guest-agent)
---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [AWX](https://github.com/ansible/awx)
------------

Description
------------

 * Ansible for oVirt Guest Agent

Requirements
------------

 *

Installation
------------

```bash
ansible-galaxy install wluisaraujo.ansible_ovirt_guest_agent
```

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
    - ovirtguestagent
...
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
