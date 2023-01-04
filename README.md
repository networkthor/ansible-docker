## Preparing the environment

1.	Install Ansible on management node https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#id13 :

    To verify whether pip is already installed for your preferred Python:
     ```
     python3 -m pip -V
     ```
    
    Use pip in your selected Python environment to install the Ansible package:
    ```
    python3 -m pip install --user ansible
    ```

2.	Configure Ansible inventory file and configuration file ansible.cfg.


## Deploying with Ansible
The standard playbook launch command: 

```
ansible-playbook docker_install.yml

```
Launch command with custom private-key:

```
ansible-playbook --private-key <<your-private-key>> docker_install.yml

```
Dry run:

```
ansible-playbook -CD docker_install.yml

```

## Useful links:
1.	https://docs.ansible.com/ansible/latest/index.html 