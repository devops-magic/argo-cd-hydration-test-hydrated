# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/devops-magic/argo-cd-hydration-test-hydrated.git
# cd into the cloned directory
git checkout 6d0c57ecce548f25aecd9ada6a908eac30311c3f
helm template . --name-template rancher-ui --include-crds
```
