# k8deploy
Ansible playbook for deploying a kubenetes cluster

## Tested for 
- CentOS Linux release 7.6.1810
- Docker 1.13.1
- Calico v3.9
- Kubernetes v1.16.0

## Prerequisites 
The account running this ansible playbook should have passwordless ssh account to all nodes (master and slaves)

## Customization 
### Kubernetes account
Edit the "kubeacc" variable in group_vars/all to the desired account

### Hosts
Edit the hosts file to add or remove slave nodes, update the hostname and ip-address accordingly
