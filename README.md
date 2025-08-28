# learn-ansible 
# Note: Ansible is used for operating system configuration management in the OS
#Understand core components of Ansible

# Inventories
# Modules
# Variables
# Facts
# Plays
# Playbooks
# Configuration files
# https://entersoftlabs.com/certification/redhat-automation-with-ansible-ex407-certification-in-hyderabad

# Installation commands
# dnf install python3.12-pip -y
# pip3.12 install ansible
# website - https://docs.ansible.com/ansible/2.9/modules/list_of_all_modules.html

# (ansible push -

# git pull
# ansible-playbook -i $(app_name)-dev.azdevops.online, \
# -e ansible_user=manju \
# -e ansible_password=Manju@devops \
# -e ENV=dev \
# -e app_name=$(app_name) roboshop.yaml)

# (ansible pull
# - specific to individual machine - for individual machine Ansible need to be installed
#  in all machines.
# ansible-pull -i localhost, -U https://github.com/ddvmanju/Roboshop-Ansible.git
# -e ENV=dev -e app_name=frontend roboshop.yaml) 
