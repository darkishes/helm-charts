# Helm Charts

This repository contains the Helm charts for Kubernetes.

## Contribution

### Add a new Helm chart

Create a new Helm chart in the `charts` directory.

```
helm create charts/<chart-name>
```

### Update an existing Helm chart

- Make changes to the existing Helm chart
- Bump the version in the `Chart.yaml` file

## Usage

### Add Helm repository

This is a public repository, so you can add it without any authentication.

```
helm repo add darkishes https://darkishes.github.io/helm-charts/
```

Check if the repository is added successfully.

```
helm repo list
```

### Update Helm repository

```
helm repo update darkishes
```