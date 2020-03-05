[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-Workstation-blue.svg)](https://galaxy.ansible.com/wluisaraujo/workstation)  [![Build Status](https://travis-ci.org/wluisaraujo/ansible-role-workstation.svg?branch=master)](https://travis-ci.org/wluisaraujo/ansible-role-workstation)
---
## IaC: with [Ansible](https://www.ansible.com) role to configure [Desktop Environment](https://getfedora.org/pt_BR/workstation/)
------------

Description
------------

 * Configurações básicas para um DesktopLinux
	- Adiciona a tarefa agendada vm.drop_caches
	- Regrinha de hosts.allow, capturando todas conexões (tcpwrapper)

Requirements
------------

 *

Installation
------------

```console
vagrant@localhost:~$ ansible-galaxy install wluisaraujo.workstation
vagrant@localhost:~$ ansible-galaxy install -r wluisaraujo.workstation/requirements.txt
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
    - workstation
...
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
