# Ansible Roles – les-04

Dit project bevat twee Ansible-rollen: één voor het configureren van een webserver en één voor het configureren van een databaseserver. Deze rollen maken deel uit van les 04 van de IT-opleiding en kunnen worden gebruikt om snel een eenvoudige LAMP-stack uit te rollen met Ansible.

## 🔧 Roles

### `web`
- Installs Apache and PHP
- Deploys an `index.php` file
- Starts and enables the Apache service

### `db`
- Installs MySQL server
- Ensures MySQL is running
- Creates a new MySQL user
- Installs PyMySQL (required for Ansible to communicate with MySQL)


## Bron
https://chatgpt.com/share/682ec4ed-40bc-8002-ac3d-00949e656a4a