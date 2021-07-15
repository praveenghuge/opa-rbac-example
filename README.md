# opa-rbac-example
## Open Policy Agent


### To checked for allowed user

```
go run main.go bundle/bundle.tar.gz < input/allowed/input.json
```

### To checked for deny user

```
go run main.go bundle/bundle.tar.gz < input/deny/input.json
```
