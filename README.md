# AnsibleAssignment

## Description
This repo contains an Ansible playbook to deploy a Flask application behind HAproxy load balancer across 3 servers.

## Files
- `site.yaml`: Main Ansible playbook that sets environment.
- `hosts`: Inventory file
- `README.md`: This file
- `haproxy.cfg.j2` - HAproxy configuration template
- `application2.py` - flask application
- `flasapp.service` - application service

## How to Run
```bash
ansible-playbook -i hosts site.yaml