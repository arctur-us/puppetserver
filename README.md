# Puppet Server
Runs Puppet master on CentOS server with Ansible

## Installation
The server must be accessible via ssh by `centos` user, who has to have `sudo` permissions. Also public key authentication must be enabled. The IP address could be changed in _hosts_ file.

### Dependencies
* [ansible] (https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)

### User installation
Download the repository from git and run locally on a terminal:
```
git clone https://github.com/yerbolkhassen/puppetserver.git
cd puppetserver
ansible-playbook playbook/all.yml -i hosts
```

## Contributors
Yerbol Khassen
