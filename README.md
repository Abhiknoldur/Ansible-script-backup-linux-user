# Ansible-script-backup-linux-use

Just add/edit users you want to backup in backup.sh in place of usr1 usr2 and run ansible-playbook with root user

Use command:

> ansible-playbook -i <inventory_file> backup.yaml -u root -k 
