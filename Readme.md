# ARM Compatible Helm Charts

This repository contains Helm charts that are compatible for ARM devices, such as the Raspberry Pi 4.

## Usage

### Prerequisites

- Kubernetes 1.19+
- Helm 3.2.0+


### Install Helm

Helm is a tool for managing Kubernetes charts. Charts are packages of pre-configured Kubernetes resources.

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

To install Helm, refer to the [Helm install guide](https://github.com/helm/helm#install) and ensure that the `helm` binary is in the `PATH` of your shell.

### Add Repo

Once Helm has been set up correctly, add the repo as follows:

  helm repo add <alias> https://andrijdavid.github.io/charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
<alias>` to see the charts.

To install the <chart-name> chart:

    helm install my-<chart-name> andrijdavid/<chart-name>

To uninstall the chart:

    helm delete my-<chart-name>


