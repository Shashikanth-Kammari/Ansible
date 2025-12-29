# Ansible

#If we want to list the hosts command is

ansible -i inventory.ini all --list-hosts

#If we want list from web

ansible -i inventory.ini web --list-hosts

#If we want run playbook

ansibl-playbook -i inventory.ini -e ansible_user=ec2-user -e ansible_password=Devops321 <filename.yaml>