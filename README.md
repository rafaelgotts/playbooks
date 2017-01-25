# playbooks


The ansible playbooks for the computers that i use

## Install Ansible

### Debian family
```bash
sudo apt-get install ansible
```

## Sudoers

If you use Debian, add the user to sudoers

## Run

### Debian family
```bash
ansible-playbook workstation.yml --ask-sudo-pass
```


## Tested on

* Debian 8.7

> This repo is based on:
https://github.com/drgarcia1986/playbooks
https://github.com/renanivo/playbooks