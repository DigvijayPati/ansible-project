# How to install Ansible

## ansible
please look into the link provided below to install ansible on your machine 

https://docs.ansible.com/ansible/2.5/installation_guide/intro_installation.html

## ansible-galaxy

1. once you install ansible in above step it automatically provides ansible-galaxy, a command line tool to install pre-packaged roles. It is hub repository for all roles created by other developers. 

2. roles can be installed with command 

```bash
ansible-galaxy install geerlingguy.pip
```

3. roles will be installed in the path:

```bash
root@username:/home/username/.ansible/roles#
geerlingguy.pip
```

