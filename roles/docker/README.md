# Docker

This Ansible role deploys docker and docker-compose to your remote machines. 

## Using this role

To use the roles inside the playbook, you need to customize some variables in defaults/main.yml. Example:
```
remote_user: ubuntu
compose_version: v2.12.2

```