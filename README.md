## Prerequisites

* **Ansible Installation**
* **Adding the SSH keys of kafka and zookeeper machines**


## Steps

1. Edit configuration file ```group_vars/all``` based on your reqiurements and environment.
2. Execute ```ansible-playbook --private-key=<AWS_key_file> -u ubuntu kafka.yml```

# Notes

* In one of my Macs I got the error described in [https://github.com/ansible/ansible/issues/5734](https://github.com/ansible/ansible/issues/5734). If you are getting the same error please use the ```inventory``` file provided (```ansible-playbook --private-key=<AWS_key_file> -u ubuntu -i inventory kafka.yml```).
