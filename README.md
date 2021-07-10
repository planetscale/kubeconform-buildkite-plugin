# Kubeconform Buildkite Plugin

A [Buildkite plugin](https://buildkite.com/docs/agent/v3/plugins) that runs [kubeconform](https://github.com/yannh/kubeconform) against Kubernetes configurations.

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
