[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-oVirt%20SGuestAgent-blue.svg)](https://galaxy.ansible.com/wluisaraujo/ovirtguestagent) [![Build Status](https://travis-ci.org/wluisaraujo/ansible-role-ovirtguestagent.svg?branch=master)](https://travis-ci.org/wluisaraujo/ansible-role-ovirtguestagent)
---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [oVirtGuestAgent](https://www.ovirt.org)
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
user@localhost:~$ ansible-galaxy install wluisaraujo.ovirtguestagent
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
