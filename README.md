# workstation
## Prepare workstation
```
ansible-playbook -i scripts/ansible/inventory.yaml scripts/ansible/playbook.yaml
```


## ssh with cert
1. Change cert file permission `chmod 0400 ~/Downloads/pem_ibmcloudvsi.pem`
2. Login
```
ssh -i ~/Downloads/pem_ibmcloudvsi.pem -p 2223 itzuser@169.59.6.199 
```

