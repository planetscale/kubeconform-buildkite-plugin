# Kubeconform Buildkite Plugin

## Example

```yml
steps:
  - plugins:
      - shellcheck#v1.1.2:
          path: config/kubernetes/base
          kustomize: true
          strict: true
```
