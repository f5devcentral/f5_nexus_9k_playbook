![Image of Topology](https://github.com/f5alliances/f5n9kplaybook/blob/master/f5n9k1.png)
## How to use the Repo
- We have three yml files
- main.yml :-> Imports yml files of Nexus 9000 & F5 BIG-IP 
- nxos_access.yml :-> Has the nexus configuration for VPC, Vlans, trunk ports etc
- f5.yml :-> Has the configuration for BIG-IP, the module configures VIP, Pool, Members, Vlan and Vlan trunk, Self IP
- delete_f5.yml :-> Can be used to remove the F5 BIG-IP configuration
- Download the yml files in your Ansible environment and update the host file accordingly

## How to Run ansible Playbook

```
ansible-playbook main.yml

```

