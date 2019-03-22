## install docker on local machine using ansible

### step 1 : install pre-packaged role for docker i.e. geerlingguy.docker

```bash
$ ansible-galaxy install geerlingguy.pip
$ ansible-galaxy install geerlingguy.docker
```

### step 2 : run ansible playbook which runs above installed role

```bash
$ ansible-playbook local.yml --user=username --extra-vars "ansible_sudo_pass=xxxxxx"
```

Note:update the fields username & xxxxxxx which is password for your username 