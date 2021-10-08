# kubernetes-sigs

This repository will use by [kube-ansible](https://github.com/buxiaomo/kube-ansible).

## cilium

```
helm repo add cilium https://helm.cilium.io/
helm install cilium cilium/cilium --version 1.10.0 --namespace kube-system --set prometheus.enabled=true \
--set operator.prometheus.enabled=true --dry-run
```