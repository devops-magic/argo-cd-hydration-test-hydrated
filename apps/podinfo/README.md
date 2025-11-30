# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/devops-magic/argo-cd-hydration-test-hydrated.git
# cd into the cloned directory
git checkout 3139280bb623e5f08ce3d812c82423ef8c194d0c
helm template . --name-template podinfo --include-crds
```
