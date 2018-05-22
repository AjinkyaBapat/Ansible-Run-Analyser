[![CircleCI](https://circleci.com/gh/AjinkyaBapat/Ansible-Run-Analyser/tree/master.svg?style=svg&circle-token=7f1296f39d95b79a100375ad55a2299c4c77b4a7)](https://circleci.com/gh/AjinkyaBapat/Ansible-Run-Analyser/tree/master) [![CircleCI token](https://img.shields.io/circleci/project/github/RedSparr0w/node-csgo-parser/master.svg?style=plastic)](https://circleci.com/gh/AjinkyaBapat/Ansible-Run-Analyser)

ARA
=========

Ansible role to install "ARA" on your system.  
Clone this repo & run `Playbook.yml`. That's it!

`ansible-playbook --ask-become-pass Playbook.yml`

Requirements
------------

An operating system with `apt` based package management (e.g., Debian, Ubuntu, etc.).

Role Variables
--------------

Role variables are stored in `roles/ARA/defaults/main.yml`

* ara_webserver_port : Port to be used for ARA. Defaults to `9191`.
* ara_webserver_ip: IP address to be used for ARA. Defaults to the value of `ansible_default_ipv4` fact.

Dependencies
------------

None

Example Playbook
----------------

Here's a sample playbook code that you can use to call your "ARA" role.

    - hosts: localhost
      roles:
         - ARA

Author Information
------------------

Ajinkya
