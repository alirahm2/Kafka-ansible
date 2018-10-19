## Prerequisites

* **Ansible Installation**
* **Add the SSH keys of kafka and zookeeper machines**


## Steps

1. Edit configuration file ```group_vars/all``` based on your reqiurements and environment.
2. Execute ```ansible-playbook --private-key=<AWS_key_file> -u ubuntu kafka.yml```

