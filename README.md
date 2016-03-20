# ipset rules

Ansible playbook to handle ipset rules.

```bash
grep "] Ban" /var/log/fail2ban.log | awk '{print $7}' | sort -u
grep "] Ban" /var/log/fail2ban.log |egrep '03-(19|20)' | awk '{print "add blacknets "$7}' | sort -u
```
