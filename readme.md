# 部署说明

## 1. 安装Bitwarden

```sh
#创建Namespace
kubectl create ns infr-bitwarden
#安装bitwarden
helm install bitwarden --namespace infr-bitwarden ./ 
```

# 2. 卸载Bitwarden

```bash
helm uninstall bitwarden --namespace infr-bitwarden ./ 
```
