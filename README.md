# Helm chart for deploying Firefly III to K8s

Bare bones helm chart for deploying [Firefly III](https://www.firefly-iii.org/) to k8s.

see [values.yaml](Firefly III/values.yaml) for configurations.

Install using Helm v3:

```
helm repo add flipenergy https://flipenergy.github.io/k8s-homelab/
helm install my-release flipenergy/Firefly III
```
