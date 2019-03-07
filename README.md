[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-desktop-environment.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-desktop-environment)
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
    - iac-ansible-desktop-environment
...    
```

License
-------

[GPLv3](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
