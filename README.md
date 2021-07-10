# Kubeconform Buildkite Plugin

## Example

```yml
steps:
  - plugins:
      - planetscale/kubeconform#main:
          path: config/kubernetes/base
          kustomize: true
          strict: true
```
