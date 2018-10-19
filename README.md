## Prerequisites

* **Ansible Installation**
* **Add the SSH keys of kafka and zookeeper machines**


## Steps

1. Edit configuration file ```group_vars/all``` based on your reqiurements and environment.
2. Edit Kafka and Zookeeper configuration file in ```roles/kafka/templates/``` and ```roles/zookeeper/templates/```
3. Edit the ip address, broker_id ,and zid of the Kafka and Zookeepr machines in the inventory file
4. Execute ```ansible-playbook -i inverntory kafka.yml```

