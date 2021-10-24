# Week_6_Ansible
## Configuration Management with Ansible

__Deploy and configure the Node Weight Tracker application for several virtual machines using Ansible.__

#
__Before using this project the following files should be edited:__
>hosts &emsp;&emsp;&emsp;__*# nodes ip's*__

In group_vars:

>all.yml

>production.yml 

>staging.yml

__Read documentation in source files.__
#

__To run the main playbook 'site.yml' run:__

    ansible-playbook -i hosts site.yml
