Ansible AWS Windows
===================

Uses Ansible to launch a Windows AMI in AWS and configure it to allow
management by Ansible over WinRM.

```
ansible-playbook -i hosts aws-windows.yml --ask-become-pass --ask-vault-pass
```
