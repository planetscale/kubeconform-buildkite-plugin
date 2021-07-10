# Kubeconform Buildkite Plugin

## Example

```yml
steps:
  - plugins:
      - planetscale/kubeconform#v0.0.1:
          files: config/kubernetes/base/*.yml
          kustomize: true
```

## License

The contents of this repository are licensed under the Apache 2.0 License. See [LICENSE](LICENSE).
