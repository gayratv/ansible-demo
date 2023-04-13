![img.png](img.png)

ansible-inventoryкоманду для проверки и получения информации о вашем инвентаре Ansible:

ansible-inventory -i inv --list


web - группа

ansible web -i inv -m ping


https://www.digitalocean.com/community/tutorials/how-to-set-up-ansible-inventories

Хост может быть частью нескольких групп. 

[webservers]
203.0.113.111
203.0.113.112

[dbservers]
203.0.113.113
server_hostname


Настройка псевдонимов хостов
server1 ansible_host=203.0.113.111
