# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/mboussaa3/argocd-example-apps
# cd into the cloned directory
git checkout b263eb7e939e89d93d22f5f0da7e657e470b3a49
helm template . --name-template development-helm-guestbook --namespace development --include-crds
```
