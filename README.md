# simple-ansible

Simple ansible setup.

# To Run

`ansible-playbook -kv {setup.yml} -i {hosts.yml} -c paramiko`

# After Install

Needs UFW:

```
ufw default deny incoming
ufw default allow outgoing
ufw allow 80
ufw allow 443
ufw allow ssh
ufw allow ntp
ufw enable
```

# To Do

```
Backups
Log rotate
Postgres hba config
```
