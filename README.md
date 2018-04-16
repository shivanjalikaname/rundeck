Rundeck Role for API automation with Ansible 2.5
=========================================

This is the rundeck role tested on centos 7 with using rundeck api token auth method

Requirements
------------

* Need Up and Running Rundeck server
* Get the token from rundeck profile-admin 
* Create the job defination to submit to rundeck server


Role Variables
--------------

The variables which are used here are RUNDECK_SERVER, PROJECT_NAME and RUNDECK_AUTH_TOKEN. These are defined in vars/main.yml

Example Playbook
----------------

Including an example of how to use role. Create rundeck.yml with :

    - hosts: servers
      roles:
         - rundeck

Run it by  -  ansible-playbook -i hosts rundeck.yml

