# DaSilva2010 Helm Charts
[Helm](https://helm.sh) repo for Docker images build by me which can be installed on [Kubernetes](https://kubernetes.io)

### Add Helm repository

To install the repo just run:

```bash
helm repo add dasilva2010 https://dasilva2010.github.io/helm/
helm repo update
```

### Helm Charts

* [papaya](https://dasilva2010.github.io/helm/charts/papaya)

  ```bash
  helm install my-papaya dasilva2010/papaya
  ```
  
* [mrbs](https://dasilva2010.github.io/helm/charts/mrbs)

  ```bash
  helm install my-mrbs dasilva2010/mrbs
  ```