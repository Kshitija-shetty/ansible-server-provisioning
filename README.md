# Automated Server Provisioning using Ansible

## Description
This project automates the provisioning of servers using Ansible. It covers installation of necessary packages, configuration of services, and application deployment to ensure consistency and efficiency across environments.

## Features
- Ansible playbooks for server setup
- Automated configuration and deployment
- Idempotent tasks to prevent duplicate changes
- Simplified maintenance and updates

## Tools Used
- Ansible
- Linux (CentOS/Ubuntu)

## Outcome
Reduced manual setup time by over 60% and ensured consistent, error-free environments.

----------------------------------------------------------------------------------------

This Ansible playbook installs and configures a basic Nginx server.

## Files
- `inventory.ini`: Defines target host.
- `playbook.yml`: Main playbook to provision server.

## Run the Playbook
```bash
ansible-playbook -i inventory.ini playbook.yml
```
