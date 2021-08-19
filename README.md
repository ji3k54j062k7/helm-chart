# helm-chart

## helm的chart仓库地址为：https://ji3k54j062k7.github.io/helm-chart

## 本Chart仓库的使用方法

1、添加chart仓库
```
# helm repo add myrepo https://ji3k54j062k7.github.io/helm-chart
```

2、添加成功
```
# helm repo list
NAME  	URL                                   
myrepo	https://ji3k54j062k7.github.io/helm-chart
```

3、搜索chart包
```
# helm search repo
NAME                              	CHART VERSION	APP VERSION	DESCRIPTION                                   
myrepo/free5gc-control-plane      0.1.0           v3.0.4          A Helm chart for Kubernetes
myrepo/free5gc-ueransim           0.1.0           v2.1.7          A Helm chart for Kubernetes use ueransim test f...
myrepo/free5gc-user-plane         0.1.0           v3.0.4          A Helm chart for Kubernetes
```

4、安装chart包
```
# helm install xxx myrepo/free5gc-control-plane
```

xxx为relaese名字
