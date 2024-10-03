# Misc Helm-charts

## 'blank' - a BYOO (bring-your-own-objects) chart

```yaml
# values.yaml
objects:
  - apiVersion...

  - apiVersion...
...
```

This will result in all objects rendered as yaml.

Silly? Yes.

But sometimes usable when handling ArgoCD and all you want is an Application that is 100% custom yaml.
