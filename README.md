# op-infra
OctopOS Prime Infrastructure

# Development Environment

## Kubernetes

### Namespace

```bash
kubectl create namespace octopos-prime
```

### Secrets

```bash
kubectl create secret generic postgres-secret --from-literal=password=<your-password>
kubectl create secret generic pgadmin-secret --from-literal=password=<your-password>
kubectl create secret generic redis-secret --from-literal=password=<your-password>
```

