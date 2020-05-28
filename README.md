# Ansible docker instalation
A Simple Ansible playbook to install docker

## Warning 
This playbook only works on ubuntu

## Execute on localhost
Add "localhost ansible_connection=local" in the inventory file and run the command:
```sh
$ ansible-playbook playbook.yml --ask-become-pass
```
## Execute on remote machines
Fulfil the inventory file with you remote servers and run teh command
```sh
$ ansible-playbook playbook.yml
```
