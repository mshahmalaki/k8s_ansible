# k8s_ansible
Setup Kubernetes Cluster with Vagrant & Ansible

Setup:
```bash
vagrant up
```

Login Master:
```bash
vagrant ssh k8s-master
```

To apply yaml files:
```bash
cd /vagrant/k8s.yaml.d
kubectl apply -f ...
```

