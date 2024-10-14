# Install EKS

Please follow the prerequisites doc before this.

## Install using Fargate

```
eksctl create cluster --name kube-cluster-name --region us-east-1 --fargate
```

## Delete the cluster

```
eksctl delete cluster --name kube-cluster-name --region us-east-1
```



