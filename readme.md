![img.png](img.png)

### Vault 
Пароль от vault лежит в файле 

~/gayrat/.pass

### Vault
ansible-vault encrypt  --vault-password-file ~/gayrat/.pass group_vars/deploy/vault.yml
ansible-vault decrypt --vault-password-file ~/gayrat/.pass group_vars/deploy/vault.yml

### Inventory
ansible-inventory -i inventory --list --vault-password-file ~/gayrat/.pass