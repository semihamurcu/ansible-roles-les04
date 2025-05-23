# Ansible Roles – les-04

This project contains two Ansible roles: one for configuring a **web server** and one for configuring a **database server**. These roles are part of lesson 04 of the IT program and can be used to quickly deploy a basic LAMP stack using Ansible.

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

