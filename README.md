# ansible101

`1. Fix host ip`

`2. Add public key to host in ~/.ssh`

`3. run command ansible-playbook -v playbook.yml`

Self Learning > https://docs.ansible.com/

---

#### Run commnad playbook
- install mariadb
```bash
ansible-playbook --private-key <path_ssh_key> playbook/install-mariadb.yml
```
