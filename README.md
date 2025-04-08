# Cluster Configuration with Argo CD

This repo contains Kubernetes cluster configuration resources managed through GitOps using Argo CD.

## Resources
- Namespace: `dev`
- Role and RoleBinding for limited access to the `dev` namespace

## Usage
Add this repo to Argo CD as an app to automatically sync and manage these cluster resources.
