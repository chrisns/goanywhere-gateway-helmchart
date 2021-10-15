# Help Systems GoAnywhere Gateway

## Usage

```
helm install \
  --set license=$(cat licensefile|base64) \
  goanywhere \
  https://github.com/chrisns/goanywhere-gateway-helmchart/archive/refs/heads/main.tar.gz
```

## Remove

```
helm uninstall goanywhere
```
