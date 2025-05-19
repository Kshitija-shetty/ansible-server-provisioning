# Automated Server Provisioning using Ansible

This Ansible playbook installs and configures a basic Nginx server.

## Files
- `inventory.ini`: Defines target host.
- `playbook.yml`: Main playbook to provision server.

## Run the Playbook
```bash
ansible-playbook -i inventory.ini playbook.yml
```
