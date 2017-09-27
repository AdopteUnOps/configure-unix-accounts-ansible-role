# configure-unix-accounts-ansible-role

Ansible role to configure local unix accounts.

Role Variables
--------------

```
ssh_users:
    - name: myuser
      key: "ssh-rsa ZZZZZYOURSSHKEY"
      password: "changeme"
former_ops_users:
    - name: mygenericaccount
```

License
-------

Apache License 2
