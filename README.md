# HelmTemplate

Helm Template for Kubernetes cluster deployment

## Getting started

# Install Helm 

- [ ] [install from source](https://helm.sh/docs/intro/install/#from-script)
```
curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3
chmod 700 get_helm.sh
./get_helm.sh
```

- [ ] [install using snap](https://helm.sh/docs/intro/install/#from-snap)
```
sudo snap install helm --classic
```

# Use Helm Template to deploy microservice in Kubernetes

- [ ] [install microservice from Kubernetes](https://helm.sh/docs/intro/using_helm/#helm-install-installing-a-package)
```
helm install @app_name --set image=@app_image --set Namespace=@app_namespace
```

- [ ] [upgrade microservice from Kubernetes](https://helm.sh/docs/intro/using_helm/#helm-upgrade-and-helm-rollback-upgrading-a-release-and-recovering-on-failure)
```
helm upgrade @app_name --set image=@app_image --set Namespace=@app_namespace
```

- [ ] [uninstall microservice from Kubernetes](https://helm.sh/docs/intro/using_helm/#helm-uninstall-uninstalling-a-release)
```
helm uninstall @app_name
```