# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/emirot/argocd-example-apps
# cd into the cloned directory
git checkout 203980e824084af7589568cb1ce0beeada0024e9
helm template . --name-template development-helm-guestbook --include-crds
```
