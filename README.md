```
skaffold build -f skaffold.yaml --file-output=out.json
```
```
skaffold deploy -a out.json
```
```
skaffold dev --digest-source='local' -f skaffold.yaml
```
```
helm upgrade --install masoud-go-hello-world -f chart/env-values/values.yaml chart --wait --atomic
```