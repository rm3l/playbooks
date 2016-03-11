Playbooks
=========

[![Build Status](https://travis-ci.org/drgarcia1986/playbooks.svg)](https://travis-ci.org/drgarcia1986/playbooks)

The ansible playbooks that I use.

Install Ansible
---------------

```bash
sudo apt-get install ansible
```

Run
---

```bash
ansible-playbook workstation.yml --ask-sudo-pass
```

Notes
-----

In Xubuntu 14.04 is necessary add parameter `validate_certs=no` in Vim configuration task (for Ubuntu 12.04 is not necessary).

> This repo is based on https://github.com/renanivo/playbooks
