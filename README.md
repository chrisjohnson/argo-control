# argo-control

This repo is used to control the installation and configuration of applications onto kubernetes clusters.

Its purpose is to act as a monorepo for all clusters, and as such it takes a cluster-centric view of things.

Each cluster gets a top-level folder which includes both the argocd Application / ApplicationSet definitions, as well as the individual helm chart configurations.

Note that this repository does not actually house the application helm charts themselves, this is merely the *instance-specific configuration* of those helm charts.
