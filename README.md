# yoyo-linux-ansible-scripts

Some Ansible scripts that will install some required packages

## chrome-linux.yml

Installs latest version of chrome

Run using:

ansible-playbook --ask-sudo-pass chrome-linux.yml 

## common-apps.yml

Install required packages for platform and retailer-tools

Run using:

ansible-playbook --ask-sudo-pass common-apps.yml 

## docker.yml

Installs docker and docker-compose. Also adds current user to the docker group. 

**NOTE: Current user must logout and back in again for docker to work**

Run using:

ansible-playbook --ask-sudo-pass docker.yml

## firewall.yml

Adds some entries to the firewall that blocks some incoming ports like SSH, RabbitMQ, Postgres & Redis  

**NOTE: Current user must logout and back in again for docker to work**

Run using:

ansible-playbook --ask-sudo-pass firewall.yml

## pycharm.yml

Installs the professional version of pycharm. Also installs python3-pip and cython  

Run using:

ansible-playbook --ask-sudo-pass pycharm.yml

## yarn.yml

This is required for Engage AKA ABI to be run   

Run using:

ansible-playbook --ask-sudo-pass yarn.yml

