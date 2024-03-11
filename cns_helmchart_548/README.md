<!--- app-name: CNS -->

# Robin CNS 

Highest performing cloud-native storage stack for any Kubernetes on-premises or in any cloud with special focus on application-aware data management and operational automation.

[Overview of Robin CNS](https://docs.robin.io/storage/5.3.14/overview.html)


## TL;DR

```console
git clone "<repository>"
cd "<repository>"
helm install cns . 
```

## Introduction

This chart bootstraps a 

## Prerequisites

- Kubernetes 1.19+
- Helm 3.2.0+

## Installing the Chart

To install the chart with the release name `cns`:

```console
git clone "<repository>"
cd "<repository>"
helm install cns . 
```

These commands deploy Robin CNS on the Kubernetes cluster in the default configuration. 

> **Tip**: List all releases using `helm list`

## Uninstalling the Chart

To uninstall/delete the `my-release` deployment:

```console
helm delete cns 
```

The command removes all the Kubernetes components associated with the chart and deletes the release.

## Parameters



### Common parameters

| Name                      | Description                                                                                               | Value           |
| ------------------------- | --------------------------------------------------------------------------------------------------------- | --------------- |
| `replicaCount`             | The number of replicas                                     | `""`            |
| `image.repository`            | Robin CNS Image              | `""`            |
| `image.pullPolicy`        | Image Pull Policy                                                    | `""`            |
| `image.tag`       | Version of the Robin CNS image                                                            | `""`            |
