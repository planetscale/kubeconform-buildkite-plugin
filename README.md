# Kubeconform Buildkite Plugin

## Example

```yml
steps:
  - plugins:
      - planetscale/kubeconform#v0.0.1:
          path: config/kubernetes/base
          kustomize: true
          strict: true
```
