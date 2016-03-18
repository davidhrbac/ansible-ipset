# ipset rules

Ansible playbook to handle ipset rules.

```bash
grep "] Ban" /var/log/fail2ban.log | awk '{print $7}' | sort -u
```
