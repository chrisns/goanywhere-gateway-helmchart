# Help Systems GoAnywhere Gateway

[![Lint and Test Charts](https://github.com/chrisns/goanywhere-gateway-helmchart/actions/workflows/lint-test.yaml/badge.svg)](https://github.com/chrisns/goanywhere-gateway-helmchart/actions/workflows/lint-test.yaml)[![Security Scanning](https://github.com/chrisns/goanywhere-gateway-helmchart/actions/workflows/security.yml/badge.svg)](https://github.com/chrisns/goanywhere-gateway-helmchart/actions/workflows/security.yml)

## Usage

```bash
# where ./licensefile is the license

$ helm repo add goanywhere https://chrisns.github.io/goanywhere-gateway-helmchart
$ helm install \
  --set-file=license=licensefile \
  goanywhere \
  goanywhere/goanywhere-gateway
```

## Remove

```bash
$ helm uninstall goanywhere
```
