# GitOps Example Apps

This repository contains example applications for demoing ArgoCD functionality. 

| Application | Description |
|-------------|-------------|
| [guestbook](guestbook/) | A hello word guestbook application as plain YAML |
| [pushwfapp](pushwfapp/) | A demo app for testing as plain YAML |
| [ksonnet-guestbook](ksonnet-guestbook/) | The guestbook application as a ksonnet app |
| [helm-guestbook](helm-guestbook/) | The guestbook application as a Helm chart |
| [jsonnet-guestbook](jsonnet-guestbook/) | The guestbook application as a raw jsonnet |
| [kustomize-guestbook](kustomize-guestbook/) | The guestbook application as a Kustomize app |
| [pre-post-sync](pre-post-sync/) | Demonstrates Argo CD PreSync and PostSync hooks |
| [helm-dependency](helm-dependency/) | Demonstrates how to customize an OTS (off-the-shelf) helm chart from an upstream repo |
| [blue-green-deploy](blue-green-deploy/) | Demonstrates an Argo CD Sync hook which performs a blue/green deployment |
| [sock-shop](sock-shop/) | A microservices demo application (https://microservices-demo.github.io) |
| [plugins](plugins/) | Applications which demonstrate config management plugins usage |
