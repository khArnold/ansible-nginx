# ansible-nginx
sample of playbook for nginx installation using ansible
in this sample playbook the hosts have been defined in the inventory or hosts file (/etc/ansible/hosts) as "jenk". so make sure you defined a host of your choice before using this playbook.
Also make sure you priority created templates directory with an index.html.j2 file in it. touch your index file and put your content in it before running your playbook.
importantly make sure that your VMs or servers have the port 80 available and not taken by any app, otherwise you will have to manually modify your nginx.conf file and assign a desired or available port before successfully executing your playbook.
