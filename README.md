# Description

Playbook for testing the dirty cow vulnerability (CVE-2016-5195).

# Dependencies

* local user on the system with sudo priveleges

# Run

```
ansible-playbook -i host, check.yml -u jondoe -k -K
```

# Links

* http://dirtycow.ninja
