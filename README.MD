
With kustomize 5.0.3 do:


kustomize build ./sub-base | grep nodeAffinity

You'll get 
```
nodeAffinity: "null"
```

instead of 
```
nodeAffinity: null
```
