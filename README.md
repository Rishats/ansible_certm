Playbooks for usage example:
=========

1) Edit hosts file.
2) Edit group_vars all.yml
3) Ping your hosts ```ansible-playbook -i hosts -e "servers=all" playbooks/ping.yml```
4) Install CERTM ```ansible-playbook -i hosts -e "servers=all" roles/ansible_certm/ansible_certm.yml```

Vagrantfile:
=========
1) By default Vagrantfile create 4 VMs based on Centos 8.

