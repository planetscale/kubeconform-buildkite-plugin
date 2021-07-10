# Kubeconform Buildkite Plugin

## Example

```yml
steps:
  - plugins:
      - planetscale/kubeconform#v0.0.1:
          files: config/kubernetes/base/*.yml
          kustomize: true
          strict: true
```
