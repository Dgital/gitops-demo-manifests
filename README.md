# GitOps Demo: manifest repository

This repository contains source code for our [GitOps - A Practical Implementation](https://dgital.com/blog/2025/06/17/gitops-practical-implementation) case study.
It stores the generated Kubernetes manifests by the devops-cli tool. The contents of the repository is watched by FluxCD and automatically applied to the cluster(s).

## Branching strategy

Each environment has its own branch, to avoid conflicts. Naming convention: `<cluster-name>/<env-name>`
