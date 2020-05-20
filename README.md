# Ansible LAMP playbook.
This is a playbook to automate the deployment of sample template e-commerce application in LAMP architecture by using Ansible in linux centOS.
Playbook allows you to deploy services packages and applicaton on x hosts contained in inventory.txt using the centOS environment as the controller.

## Command call:

```bash
ansible-playbook playbook-application.yaml -i inventory.txt
```

## Requirements:
Installed ansible on the controller and the ability to connect to target hosts using ssh.

## Main Steps in playbook:

- Firewall installation

- MariaDB installation

- Configuring firewall for Database

- Configuring Database

- Loading Product Inventory Information to database

- Installing required packages

- Http configurattion

- Downloading template LAMP app

- Index.php update
