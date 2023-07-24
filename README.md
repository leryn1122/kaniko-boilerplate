
# Kaniko Boilerplate

## TL;DR

A simple kaniko boilerplate.

```bash
kubectl create secret docker-registry kaniko-registry \
  --docker-server="harbor.leryn.top" \
  --docker-username=admin \
  --docker-password=******
```

```bash
kubectl apply -f deploy/pod.yaml
```
