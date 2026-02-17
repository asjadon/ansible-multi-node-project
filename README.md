# Ansible Multi-Server Project

## Project Overview
This project uses Ansible to:

- Install Nginx on 2 Web Servers
- Deploy Custom Website
- Manage 1 DB Server

## Architecture

Control Node: WSL (Laptop)
Managed Nodes:
- web1 (EC2)
- web2 (EC2)
- db1  (EC2)

## How To Run

ansible-playbook -i inventory nginx.yml

## Technologies Used

- Ansible
- AWS EC2
- Nginx
- GitHub
