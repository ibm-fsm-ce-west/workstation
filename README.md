# Prepare Workstation for Installing Cloud Paks
## Run Ansible Play books
The ansible play books tested on Ubuntu 20 LTS.

1. Update corresponding values in `scripts/ansible/inventory.yaml` 
2. Run the playbook
```
ansible-playbook -i scripts/ansible/inventory.yaml scripts/ansible/playbook.yaml
```



## ssh with cert
1. Change cert file permission `chmod 0400 <path/to/cert>`
2. Login
```
ssh -i <path/to/cert> -p <port> <user>@1<linux_server>
```

