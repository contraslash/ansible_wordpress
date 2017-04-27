# ansible_wordpress

Ansible recipes for Wordpress Creation.

Be sure to modify `host` file to target the correct IP or server name of your servers. 

> dbservers and webservers could be the same machine

To use execute:
```
ansible-playbook -u user_in_apachegroup_group -k -i hosts playbook.yml
```

> You can use root as user under you own risk


