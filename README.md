# Puppet Server
Runs Puppet master on CentOS 8 server with Ansible

## Installation
The server must be accessible via ssh by `centos` user, who has to have `sudo` permissions. Also public key authentication must be enabled. The IP address could be changed in _hosts_ file.

### Dependencies
* [ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)

### Setup
Download the repository from GitHub and run locally on a terminal:
```
git clone https://github.com/yerbolkhassen/puppetserver.git
cd puppetserver
ansible-playbook playbook/all.yml
```

## Contributor
Yerbol Khassen
