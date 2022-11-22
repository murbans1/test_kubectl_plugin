
## Usage
The following assumes you have the plugin installed via

```shell
kubectl krew install test_plugin
```

### Scan images in your current kubecontext

```shell
kubectl test_plugin
```

### Scan images in another kubecontext

```shell
kubectl test_plugin --context=context-name
```

## How it works
Write a brief description of your plugin here.