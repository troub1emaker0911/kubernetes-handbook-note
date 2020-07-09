# kubernetes-handbook
kubernetes-handbook reading note


### 关于下载kubedns镜像

*基于防火墙的限制，无法直接从gcr.io获取到kubedns相关image. 可尝试从hub.docker.com获取相关image，然后打tag即可。*
  
提供一个hub.docker.com地址：
```
https://hub.docker.com/u/anjia0532
```
<br />

以下提供一个1.14.1版本的image地址：

* gcr.io/google_containers/k8s-dns-dnsmasq-nanny-amd64:1.14.1
```
#pull command:
docker pull xuejipeng/k8s-dns-dnsmasq-nanny-amd64:v1.14.1

#打tag:
docker tag xuejipeng/k8s-dns-dnsmasq-nanny-amd64:v1.14.1 gcr.io/google_containers/k8s-dns-dnsmasq-nanny-amd64:1.14.1
```
<br />

* gcr.io/google_containers/k8s-dns-kube-dns-amd64:1.14.1
```
#pull command:
docker pull locutus1/k8s-dns-kube-dns-amd64:1.14.1

#打tag:
docker tag locutus1/k8s-dns-kube-dns-amd64:1.14.1  gcr.io/google_containers/k8s-dns-kube-dns-amd64:1.14.1 
```
<br />

* gcr.io/google_containers/k8s-dns-sidecar-amd64:1.14.1

```
#pull command:
docker pull locutus1/k8s-dns-sidecar-amd64:1.14.1

#打tag:
docker tag locutus1/k8s-dns-sidecar-amd64:1.14.1 gcr.io/google_containers/k8s-dns-sidecar-amd64:1.14.1 
```
