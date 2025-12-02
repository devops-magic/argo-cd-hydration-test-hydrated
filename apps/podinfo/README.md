# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/devops-magic/argo-cd-hydration-test-hydrated
# cd into the cloned directory
git checkout 413871df2068db2410ac3def7f05cb0e9a417c66
helm template . --name-template my-app --include-crds
```
