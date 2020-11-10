# Cloudwatch logging of an EKS cluster

## enable e.g. via yaml config file

```bash
eksctl utils update-cluster-logging --config-file eks-config.yaml --approve
```

## disable via plain commandline call

```bash
eksctl utils update-cluster-logging --name=eks-cluster --disable-types all
```
