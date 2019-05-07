[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-workstation-environment.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-workstation-environment)
---
## IaC: with [Ansible](https://www.ansible.com) role to configure [Desktop Environment](https://getfedora.org/pt_BR/workstation/)
------------

Description
------------

 * Configurações básicas para um DesktopLinux
	- Adiciona a tarefa agendada vm.drop_caches
	- Regrinha de hosts.allow, capturandos todas conexões (tcpwrapper)
	
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
    - iac-ansible-workstation-environment
...    
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)