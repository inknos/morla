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

To stop/destroy a container:
```
ansible-playbook server.yml --tags=stop-nginx -K
ansible-playbook server.yml --tags=destroy-nginx -K
```

To purge a container and its config dir:
```
ansible-playbook server.yml --tags=purge-nginx -K
```
