# helm-chart

## helm的chart倉庫地址：https://ji3k54j062k7.github.io/helm-chart

## 本Chart倉庫的使用方法

1、添加chart倉庫
```
# helm repo add myrepo https://ji3k54j062k7.github.io/helm-chart
```

2、添加成功
```
# helm repo list
NAME  	URL                                   
myrepo	https://ji3k54j062k7.github.io/helm-chart
```

3、找chart
```
# helm search repo
NAME                                    CHART VERSION   APP VERSION     DESCRIPTION
myrepo/free5gc-control-plane            0.1.0           v3.0.4          A Helm chart for Kubernetes
myrepo/free5gc-ueransim                 0.1.0           v3.1.4          A Helm chart for Kubernetes use ueransim test f...
myrepo/free5gc-user-plane               0.1.0           v3.0.4          A Helm chart for Kubernetes
```

4、安装chart
```
# helm install xxx myrepo/free5gc-control-plane
```

xxx為relaese名字
