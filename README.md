# helm-chart

`serialt`的`chart`仓库地址为`https://serialt.github.io/helm-chart`



1、添加chart仓库

```
[root@serialt ~]# helm repo add serialt https://serialt.github.io/helm-chart
```

2、添加成功

```
[root@serialt ~]# helm repo list
NAME    URL                                 
serialt https://serialt.github.io/helm-chart
```

3、搜索chart包

```
[root@serialt ~]# helm search repo
NAME            CHART VERSION   APP VERSION     DESCRIPTION                
serialt/test    0.1.0           1.16.0          A Helm chart for Kubernetes
```

4、安装chart包

```
[root@serialt ~]# helm install cc serialt/test
```
