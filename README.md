# `openshift_htpasswd_oauth`

## Installation

```
ansible-galaxy install https://github.com/jkupferer/ansible-role-openshift_htpasswd_oauth/archive/master.tar.gz#/openshift_htpasswd_oauth
```

## Usage

Example Playbook:
```
- name: Configure htpasswd OAuth
  hosts: localhost
  gather_facts: false
  roles:
  - openshift_htpasswd_oauth
  vars:
    openshift_htpasswd_users:
    - name: alice
      password: p4ssw0rd
    - name: bob
      password: p4ssw0rd
```
