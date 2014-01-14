# simple-ansible

Simple ansible setup.

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

```
# Backups
# Log rotate
# Postgres hba config
