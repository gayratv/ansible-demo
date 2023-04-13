![img.png](img.png)

ansible-inventoryкоманду для проверки и получения информации о вашем инвентаре Ansible:

ansible-inventory -i inv --list


web - группа

ansible web -i inv -m ping