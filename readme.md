# Kubernetes Tools

Utility scripts for Kubernetes. Both take a namespace as a parameter; if omitted, the
namespace configured for the default context in `~/.kube/config` will be used.

## Scripts

*   `kubeinfo`: Dumps info on every object in a namespace.

*   `kubemonitor`: Runs the above in a watch loop.

*   `kubetidy`: Performs a cleanup on a namespace, deleting evicted pods
    and old replica sets.

*   `kubelogs`: Tail the logs of pods in a namespace. By default the logs of all pods
     all tailed. Use the `-i|--include` option to include specific pods or `-e|--exclude`
     to exclude specific pods (these switches can take multiple strings separated). This
     command also takes an optional `-l|--lines` parameter to define how many lines to
     include in the tail (default is 10).

## Installation

The scripts can be copied to  /usr/local/bin by running `install`.
