# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/devops-magic/argo-cd-hydration-test-hydrated.git
# cd into the cloned directory
git checkout 8caa28c4d82f32128614c19881cee7f66bd8f77b
helm template . --name-template rancher-ui --include-crds
```
