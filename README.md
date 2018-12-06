[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-desktop-environment.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-desktop-environment)
=========

Desktop Environment (Linux)
=========

Configurações básicas para um DesktopLinux
	- Adiciona a tarefa agendada vm.drop_caches
	- Regrinha de hosts.allow, capturandos todas conexões (tcpwrapper)

Requirements
------------


Role Variables
--------------


Dependencies
------------


Example Playbook
----------------

    - hosts: desktop
      roles:
         - { role: iac-ansible-desktop-environment }

License
-------

GPLv3

Author Information
------------------
