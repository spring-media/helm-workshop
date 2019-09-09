# Getting Started with Helm

Install helm on your machine and get familiar with the basic commands using the official [quickstart guide](https://docs.helm.sh/using_helm/#quickstart)

## Prerequisites

- A Kuberbetes cluster with kubectl configured to access it.

## Installing the Helm Client

On Mac, the easiest way to install Helm is to use Homebrew:

```console
$ brew install kubernetes-helm
```


## Using Helm

If this is your first time using Helm, here are the critical commands.

- `helm help`: Show help. You can get more info on a command by doing `helm COMMAND --help`, such as `helm list --help`
- `helm search STRING`: Find charts to install
- `helm install -n NAME CHART`: Install something (create a release). Example: `helm install -n my-test stable/wordpress`
- `helm status NAME`: Get the status of a release
- `helm delete NAME`: Delete the release. Example: `helm delete my-test`


Up next: [Charts](../02-charts/).
