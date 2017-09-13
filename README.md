[![CircleCI](https://circleci.com/gh/AjinkyaBapat/Ansible-Run-Analyser/tree/master.svg?style=svg&circle-token=7f1296f39d95b79a100375ad55a2299c4c77b4a7)](https://circleci.com/gh/AjinkyaBapat/Ansible-Run-Analyser/tree/master) [![CircleCI token](https://img.shields.io/circleci/project/github/RedSparr0w/node-csgo-parser/master.svg?style=plastic)](https://circleci.com/gh/AjinkyaBapat/Ansible-Run-Analyser)

ARA
=========

Ansible role to install "ARA" on your system.
Just add this folder to your "roles" folder and include it in your playbook.

Requirements
------------

None

Role Variables
--------------

ara_webserver_port : Port to be used for ARA

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
