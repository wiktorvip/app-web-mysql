## app-web-mysql

* name: app-web-mysql
* port: 9070

### Deploy:
```
kubectl apply -f https://raw.githubusercontent.com/wiktorvip/app-web-mysql/main/manifests/pod-mysql.yaml
kubectl apply -f https://raw.githubusercontent.com/wiktorvip/app-web-mysql/main/manifests/service-mysql.yaml


kubectl apply -f https://raw.githubusercontent.com/wiktorvip/app-web-mysql/main/manifests/secret-app-secret.yaml
kubectl apply -f https://raw.githubusercontent.com/wiktorvip/app-web-mysql/main/manifests/service-app-web-mysql.yaml
kubectl apply -f https://raw.githubusercontent.com/wiktorvip/app-web-mysql/main/manifests/pod-app-web-mysql-sec.yaml
```
