# Overview
Ansible playbooks to install tools on a Kubernetes cluster


# Features
- includes Longhorn and MetalLB


# Quickstart

ansible-playbook -i inventory/dev playbooks/all.yaml --user appuser

ansible-playbook -i inventory/dev playbooks/helm.yaml --user appuser
ansible-playbook -i inventory/dev playbooks/longhorn.yaml --user appuser
```

Install kubernetes-dashboard
```
ansible-playbook -i inventory/dev playbooks/kubernetes-dashboard.yaml
```

# Update Nodes
```
ansible-playbook -i inventory/dev playbooks/update-and-reboot.yaml --user appuser
```

