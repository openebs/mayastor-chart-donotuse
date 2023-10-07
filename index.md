This repository houses unstable helm charts used for Mayastor's CI. Use https://openebs.github.io/mayastor-extensions for the stable Mayastor helm chart.

# Helm Repository for Mayastor testing

## Installation Guide

### Add the repository

```bash
helm repo add mayastor-testing https://openebs.github.io/mayastor-chart-donotuse/ 
```

### Install Mayastor test chart

```bash
helm install mayastor-testing mayastor-testing/mayastor -n mayastor-testing --create-namespace
```
