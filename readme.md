# Kubernetes Helm Chart

The code is provided as-is with no warranties.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:


```
helm repo add repo-despliegue https://sosan.github.io/kube_exp/ && \
helm install mongo repo-despliegue/despliegue-mongo -n dev-mongo --create-namespace && \
helm install redis repo-despliegue/despliegue-redis -n dev-redis --create-namespace && \
helm install microservicios repo-despliegue/despliegue-microservicios -n dev-microservicios --create-namespace && \
```

All

```console
helm repo add repo-despliegue https://sosan.github.io/kube_exp/ && \
helm install despliegue repo-despliegue/despliegue-mongo-redis-api -n masivo --create-namespace
```


