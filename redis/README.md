### Install Redis through Helm:

```shell
helm upgrade --install redis bitnami/redis --namespace redis --values tools/redis/values.yaml --create-namespace
```
