# Help Systems GoAnywhere Gateway

[![Lint and Test Charts](https://github.com/chrisns/goanywhere-gateway-helmchart/actions/workflows/lint-test.yaml/badge.svg)](https://github.com/chrisns/goanywhere-gateway-helmchart/actions/workflows/lint-test.yaml)[![Security Scanning](https://github.com/chrisns/goanywhere-gateway-helmchart/actions/workflows/security.yml/badge.svg)](https://github.com/chrisns/goanywhere-gateway-helmchart/actions/workflows/security.yml)

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
