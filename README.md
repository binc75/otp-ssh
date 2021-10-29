## TOTP SSH - googleAuthenticator
Setup googleAuthenticator for SSH access on Ubuntu OS with ansible.<br>
Ansible playbook is there for learning purposes, stuff can be done differently but this is a kind of reference for myself.

## Setup
### run playbook
```bash
ansible-playbook -i inventory/hosts playbooks/otp-ssh.yaml --check
ansible-playbook -i inventory/hosts playbooks/otp-ssh.yaml
```
### ansible ping
```bash
ansible ssh_servers -i inventory/hosts -m ping
```
