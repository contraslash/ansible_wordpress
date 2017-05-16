# ansible_wordpress

Ansible recipes for Wordpress Creation.

Be sure to modify `host` file to target the correct IP or server name of your servers. 

> dbservers and webservers could be the same machine

To use execute:
```
ansible-playbook -u deploy_user -k -i hosts playbook.yml
```

Remember that deploy_user must exists in all machines defined in `host` file and must have proper permissions, in dbserver to access to a database with admin privileges and on web server to locate content in the www/html folder

> You can use root as user under you own risk


