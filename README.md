Ansible AWS Windows
===================

Uses Ansible to launch a Windows AMI in AWS and configure it to allow
management by Ansible over WinRM.

The second role configures a web application called ping.

The third role uses the
[deekayen.tls](https://galaxy.ansible.com/deekayen/tls/) galaxy role to
setup stronger TLS encryption.

```
ansible-playbook -i hosts aws-windows.yml --ask-become-pass --ask-vault-pass
```

See also
--------

Chris Church published similar functionality in the
[cchurch.win-ec2](https://galaxy.ansible.com/cchurch/win-ec2/) Galaxy
role.
