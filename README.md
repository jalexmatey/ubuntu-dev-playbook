# ubuntu-dev-playbook
Ubuntu (and it's derivatives) setup and configuration, using Ansible.

## Setup

```bash
sudo apt install ansible
ansible-galaxy install --role-file requirements.yml
ansible-playbook main.yml --tags=update --ask-become-pass # Input user password when prompted
ansible-playbook main.yml --ask-become-pass # Input user password when prompted
```
