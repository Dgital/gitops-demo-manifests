# GitOps Demo: manifest repository

This repository contains the generated Kubernetes manifests by the devops-cli tool. The contents of the repository is watched by FluxCD and automatically applied to the cluster(s).

## Branching strategy

Each environment has its own branch, to avoid conflicts. Naming convention: `<cluster-name>/<env-name>`
