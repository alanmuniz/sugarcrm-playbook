
```
Working On: Ubuntu-16.04


1- Access to the server and install Python
2- Add the IP to file: Hosts under Microplat
3- Execute the playbook with user root 
```


`Install SugarCrm Stack`

```
ansible-playbook main-sugar.yaml --user root --ask-pass
``` 
---

`Execute as another user with root privileges`

```
ansible-playbook main-sugar.yaml --user $USER --become
```

