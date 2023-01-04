# Nginx Certbot

This Ansible role deploys nginx container as reverse proxy for your web server. And deploys certbot container to autoinstall SSL-certificate to your website. 


## Using this role

To use the roles inside the playbook, you need to customize some variables in defaults/main.yml. Example:
```
webserver_ip: 192.168.10.1
webserver_port: 8080
domain_name: networkthor.info
email: admin@networkthor.info

```