# ansible-pip [![Build Status](https://travis-ci.org/futurice/ansible-pip.svg?branch=master)](https://travis-ci.org/futurice/ansible-pip)

Ansible role for Pip

# development
```
pip install ansible
ANSIBLE_ROLES_PATH=../ ANSIBLE_SSH_ARGS="-o ForwardAgent=yes" \
ansible-playbook tests/test.yml -i inventory -v
```

