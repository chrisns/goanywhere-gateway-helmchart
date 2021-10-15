# Help Systems GoAnywhere Gateway

## Usage

```
helm install \
  --set licence=$(cat licencefile|base64) \
  goanywhere \
  .
```

## Remove

```
helm uninstall goanywhere
```
