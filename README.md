# morla
Ansible scripts to configure my private server

Run with:
```
ansible-playbook server.yml -K
```

To set up individual services:
```
ansible-playbook server.yml --tags=setup-nginx -K
```

To destroy a container:
```
ansible-playbook server.yml --tags=destroy-nginx -K
```

If you have a file `password` with became password inside
```
ansible-playbook server.yml --vault-password-file=password
```
