## OpenShift Istio Service Mesh installation 

Update hosts file and run Ansible playbooks 

```
ansible-playbook -i ./hosts --tags patch-es sites.yml -vv
ansible-playbook -i ./hosts --tags istiop sites.yml -vv
```