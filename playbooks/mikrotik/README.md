Different playbooks for Mikrotik 
========================
Tested on ROS6 and ROS7


## Content examples
```yaml
mini-project:
  - fetches backups from Mikrotiks, also could encrypt + clean from junk info
playbooks:
  - check-l2tp.yml
  - collect-info.yml
  - syslog-to-logstash.yml ⚠️WARNING⚠️ This playbook is not idempotent