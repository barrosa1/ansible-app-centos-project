This is a playbook to automate the deployment of sample template e-commerce application in LAMP architecture by using Ansible in linux centOS.
Playbook allows you to deploy services packages and applicaton on x hosts contained in inventory.txt using the centOS environment as the controller.

Command call:
ansible-playbook playbook-application.yaml -i inventory.txt

Requirements:
Installed ansible on the controller and the ability to connect to target hosts ussing ssh.

Main Steps in playbook:

- Firewall instalation

- MariaDB instalation

- Configurating firewall for Database

- Configurating Database

- Loading Product Inventory Information to database

- Installing required packages

- Http configuration

- Download template LAMP app

- Update index.php
