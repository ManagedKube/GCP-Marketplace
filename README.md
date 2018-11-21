ManagedKube Kubernetes Cost Attribution
===========================

# Overview
ManagedKube’s Kubernetes Cost Attribution is an application to help you understand the cost of your Kubernetes clusters, from what each namespace or pod costs to how much disks or network traffic in the cluster costs, so you can manage your budget and optimize your cloud spend.


# Installation

## Quick install with Google Cloud Marketplace

Get up and running with a few clicks! Install this `Kubernetes Cost Attribution` app to a Google
Kubernetes Engine cluster using Google Cloud Marketplace. Follow the on-screen
instructions:
*TODO: link to solution details page*

## Command line instructions

Follow these instructions to install `Kubernetes Cost Attribution` from the command line.

### Prerequisites

- Setup cluster
  - Permissions
- Setup kubectl
- Setup helm
- Install Application Resource
- Acquire License

### Commands

Expand manifest template:
```
cd ./Chart/chart/kubernetes-cost-attribution/
helm template . > expanded.yaml
```

Run kubectl:
```
kubectl apply -f expanded.yaml
```

*TODO: fix instructions*

# Backups

*TODO: instructions for backups*

# Upgrades

*TODO: instructions for upgrades*
