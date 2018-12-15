# bootstrap-workstation
Ansible playbook for provisioning my fedora workstation.

I got tired configuring the same things every time I do new install.
This repo is mainly for my personal use. You probably don't want to run it on your system, but feel free user parts of it in your project.

It expects Fedora XFCE as a base.

### Install
```
ansible-galaxy install -r requirements.yml
ansible-playbook playbook.yml --ask-become-pass
```
