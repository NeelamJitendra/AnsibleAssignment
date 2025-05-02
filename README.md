# NSO A2 Deployment

## Description
This repo contains an Ansible playbook to deploy a Flask application behind HAproxy load balancer across 3 servers.

## Files
- `hosts`: Inventory file
- `README.md`: This file

## How to Run
```bash
ansible-playbook -i hosts site.yaml