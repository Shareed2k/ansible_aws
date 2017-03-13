# Set up your aws vpc with ansible

![N](http://i64.tinypic.com/2dsg7ch.jpg)

### Requirements

```sh
Ansible : sudo pip install ansible
Boto : sudo pip install boto
AWS CLI : sudo pip install awscli
```

### Run the playbook :

```
ansible-playbook playbook.yml -i inventory -e @vars.yml
```