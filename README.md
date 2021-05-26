# Ansible E-Commerce Project
This Ansible playbook code deploys the KodeKloud E-Commerce Website which is fictitious and just used to test this Ansible Ploybook. This code uses the LAMP stack - It uses CentOS7 version of Linux OS, Apache WebServer, MariaDB as its database & PHP scripting language.

This playbook automatically prepares & deploys the entire applications needed to run the above-mentioned KodeKloud E-Commerce website from scratch on 3 fresh Linux servers using command: 
ansible-playbook ecommerce-project-playbook.yaml -i inventory.txt

 Finally, please note that I have used the basic ssh password scheme here (although this is not recommended on production deployments) as this playbook is just for test purposes. However, again this won't work unless you first manually establish an ssh connection to login to this remote Linux Server (before issuing the above command) or you disable the host_key_checking feature in the /etc/ansible/ansible.cfg file. However, the latter method is not recommended too on production deployments where ssh keys must be used to establish the connectivity with of the Ansible controller with the remote machines.    
