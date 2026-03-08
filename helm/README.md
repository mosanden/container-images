# Advanced `helm` Image

This container image contains helm and adds several useful dependencies:
- curl
- jq
- yq
- gettext-base (e.g. envsubst)
- grep
- bash
- git
- openssl

It is based on the [k8s-helm builds provided by Lachlan Evenson](https://hub.docker.com/r/lachlanevenson/k8s-helm).
