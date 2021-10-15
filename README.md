# Help Systems GoAnywhere Gateway

## Usage

```
helm install \
  --set license=$(cat licensefile|base64) \
  goanywhere \
  .
```

## Remove

```
helm uninstall goanywhere
```
