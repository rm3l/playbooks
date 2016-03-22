# Playbooks

[![Build Status](https://travis-ci.org/drgarcia1986/playbooks.svg)](https://travis-ci.org/drgarcia1986/playbooks)

The ansible playbooks that I use.

## Install Ansible

### Ubuntu family
```bash
sudo apt-get install ansible
```
### Arch family
```bash
sudo pacman -S ansible
```

## Run

### Ubuntu family
```bash
ansible-playbook workstation.yml --ask-sudo-pass
```
### Arch family
```
ansible-playbook workstation.yml -e "ansible_python_interpreter=/usr/bin/python2" --ask-sudo-pass
```
> Default Arch python interpreter is Python 3.5

## Tested on

* Lubuntu 15
* Xubuntu 14

> This repo is based on https://github.com/renanivo/playbooks
