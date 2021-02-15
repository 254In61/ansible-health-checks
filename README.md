health_check tool summary
=============================

Tool runs through Cisco devices for baseline health checks.

Design overview
----------------
* main.yml :
    - Ansible code.
    - Runs cisco commands, using the ios_command module and ios_facts.

Requirements
------------

* Ansible 2.7.5 and above on the controlling machine.
* The remote device must be running Cisco IOS
* The remote device must support SSH

How to run
----------

* ansible-playbook health_checks.yml

Variables
---------
* credentials : Ansible script will need username & password will be needed. You can save them as a vars file.

Authors
-------
* Allan Maseghe
