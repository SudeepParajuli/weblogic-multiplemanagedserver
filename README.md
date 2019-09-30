# prerequistic : 

Keep these two file inside /roles/setup-weblogic/files 

```
server-jre-8u191-linux-x64.tar.gz
fmw_12.2.1.3.0_wls.jar
```

Dont forget to provide the write permission for all the files inside /roles/setup-weblogic/files






## To run : 

```
vagrant up
```

## run ansible playbook 

```
ansible-playbook playbook.yaml -i ansible_hosts
```


