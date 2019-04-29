# sh commands

```sh

VERSION=${VERSION}

docker pull hawsers/kubernetes-dashboard-amd64:${VERSION}
docker tag hawsers/kubernetes-dashboard-amd64:${VERSION} k8s.gcr.io/kubernetes-dashboard-amd64:${VERSION}
docker rmi hawsers/kubernetes-dashboard-amd64:${VERSION}
```
