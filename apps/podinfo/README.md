# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/devops-magic/argo-cd-hydration-test-hydrated.git
# cd into the cloned directory
git checkout 15b3bb3acac9b8b5716227558e6036409f909c98
helm template . --name-template podinfo --include-crds
```
