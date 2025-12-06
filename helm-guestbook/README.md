# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/emirot/argocd-example-apps
# cd into the cloned directory
git checkout 8851f3b5b1e7aed00bc20b0d2e8b904c455f9ec4
helm template . --name-template development-helm-guestbook --include-crds
```
