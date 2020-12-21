# Bank-Vault

* helm install vault-operator --set=etcd-operator.enabled=true --set=etcd-operator.etcdOperator.commandArgs.cluster-wide=true banzaicloud-stable/vault-operator -n bank-vault
* kubectl apply -f vault-rbac.yaml
* kubectl apply -f vault-etcd.yaml


