# Kubeconform Buildkite Plugin

A [Buildkite plugin](https://buildkite.com/docs/agent/v3/plugins) that runs [kubeconform](https://github.com/yannh/kubeconform) against Kubernetes configurations.

This plugin runs as a [`post-command`](https://buildkite.com/docs/agent/v3/hooks#available-hooks) hook, which allows the `command` property to get used to run Kustomize or other tools which generate configuration before running `kubeconform`.

## Example

```yml
steps:
  - plugins:
      - planetscale/kubeconform#v0.0.1:
          files: config/kubernetes/base/*.yml
```

## License

The contents of this repository are licensed under the Apache 2.0 License. See [LICENSE](LICENSE).
