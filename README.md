# bootstrap-workstation
Ansible playbook for provisioning my fedora workstations.

### Install
Install `ansible` and `git`
```
dnf -y install ansible git
```
Clone this repository
```
git clone https://github.com/RadekManak/bootstrap-workstation.git ~/.bootstrap
cd ~/.bootstrap
```
Install ansible node dependencies
```
ansible-playbook bootstrap-playbook.yml -i inventory.txt --ask-become-pass
```
Run playbook.
```
ansible-playbook laptop-playbook.yml --ask-become-pass -i inventory.txt
```
