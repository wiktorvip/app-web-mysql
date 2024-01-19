## app-web-mysql

* name: app-web-mysql
* port: 9070

### Deploy:
```
kubectl apply -f https://raw.githubusercontent.com/wiktorvip/app-web-mysql/main/manifests/ConfigMap.yaml
kubectl apply -f https://raw.githubusercontent.com/wiktorvip/app-web-mysql/main/manifests/Deployment.yaml
kubectl apply -f https://raw.githubusercontent.com/wiktorvip/app-web-mysql/main/manifests/Service.yaml
```
