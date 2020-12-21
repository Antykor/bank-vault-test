1] helm install vault-operator --set=etcd-operator.enabled=true --set=etcd-operator.etcdOperator.commandArgs.cluster-wide=true banzaicloud-stable/vault-operator -n bank-vault
2] kubectl apply -f vault-rbac.yaml
3] kubectl apply -f vault-etcd.yaml


