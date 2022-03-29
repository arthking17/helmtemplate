# HelmTemplate

Helm Template for Kubernetes cluster deployment

## Getting started

# Install Helm 

- [ ] install from source
```
curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3
chmod 700 get_helm.sh
./get_helm.sh
```

- [ ] install using snap
```
sudo snap install helm --classic
```

# Use Helm Template to deploy microservice in Kubernetes

- [ ] install microservice from Kubernetes
```
helm install @app_name --set image=@app_image --set Namespace=@app_namespace
```

- [ ] upgrade microservice from Kubernetes
```
helm upgrade @app_name --set image=@app_image --set Namespace=@app_namespace
```

- [ ] uninstall microservice from Kubernetes
```
helm uninstall @app_name
```