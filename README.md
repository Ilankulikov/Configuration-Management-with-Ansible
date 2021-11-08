## Week 6 Project
# Configuration Management with Ansible

__Deploy and configure the Node Weight Tracker application for several virtual machines using Ansible.__

#
The main playbook `site.yml` first running the common role which importing the application repository from github and and installing the necessary packages and then runs the environments roles to install all the dependencies and run the application as a service.


__To use this Ansible project the following files should be edited:__
- hosts &emsp;&emsp;&emsp;__*# nodes ip's*__

**group_vars:**

- all.yml

 - production.yml 

 - staging.yml

__Read the documentation in source files.__
#

__To run the main playbook 'site.yml' run:__

    ansible-playbook -i hosts site.yml
