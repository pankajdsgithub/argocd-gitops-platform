# Argo CD GitOps Platform

This repository defines GitOps practices for Azure Kubernetes workloads using Argo CD and application promotion through Git as the source of truth.

```mermaid
flowchart LR
    A[Git Repo] --> B[Argo CD]
    B --> C[AKS Cluster]
    C --> D[Apps]
    D --> E[Observability]
```
