# HTTPD_Ansible_Playbook

This Ansible Playbook accomplishes the task of installing and starting the HTTPD Server.
Generally, the task of restarting HTTPD service is not idempotent. 
This can be made idempotent by adding a keyword "changed_when".
The keyword "changed_when" explicitly tells ansible when to consider the task as Successful (or) changed.
Thus, this makes the task idempotent.
