# Ansible for Dev environment

This is a basic example of ansible for provisioning your dev environment.

## Requirements

Ansible >= 2.3

## How to use

### Setup a virtualenv (Very recomended)
Install virtualenv

```
cd ansible-roles

$ virtualenv --python=/usr/bin/python3 env
$ source env/bin/activate
$ pip install -r requirements.txt
```

### Run the playbook
```
$ ansible-playbook playbook.yml -i hosts -K
```
That's it.