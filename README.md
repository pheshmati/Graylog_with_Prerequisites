gray log installation with (java-elasticsearch & mongodb)
---

Example Inventory ==> /etc/ansible/hosts
[clients]
your_server_hostname ansible_host=192.168.235.133 (ip_server)

Example Playbook
---
```
   	- hosts: clients
  	 roles:
    	 - role: graylog
```
