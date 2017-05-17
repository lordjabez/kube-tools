# Kubernetes Tools

Utility scripts for Kubernetes. Both take a namespace as a parameter; if omitted, the
namespace configured for the default context in `~/.kube/config` will be used.

*   `kubeinfo`: Dumps info on every object in a namespace.

*   `kubemonitor`: Runs the above in a watch loop.

*   `kubetidy`: Performs a cleanup on a namespace, deleting evicted pods
    and old replica sets.

Copy them to /usr/local/bin by running `install`.
