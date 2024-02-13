``` bash
helm repo add elastic https://helm.elastic.co
```

``` bash
helm -f values.yaml install elasticsearch ./helm-charts/elasticsearch --set imageTag=8.5.1
```


