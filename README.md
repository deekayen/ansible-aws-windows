Ansible AWS Windows
===================

Uses Ansible to launch a Windows AMI in AWS and configure it to allow
management by Ansible over WinRM.

The second role configures a web application called ping.

The third role uses the deekayen.tls galaxy role to setup stronger TLS
encryption.

```
ansible-playbook -i hosts aws-windows.yml --ask-become-pass --ask-vault-pass
```
