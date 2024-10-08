---
sidebar_position: 1
---

# Certified CAPI Providers

Remember that most Cluster API Providers are upstream projects maintained by the Kubernetes open-source community.

## List of certified providers

:::note
This list is constantly evolving to reflect the ongoing development of the project.
:::

This is a list of the officially certified CAPI Providers by Turtles. These providers are covered by our test suite and we actively ensure that they work properly with the CAPI extension for Rancher.

| Platform        | Code Name                      | Provider Type            | Docs                     |
|-----------------|--------------------------------|--------------------------|--------------------------|
| **RKE2**        | CAPRKE2                    | Bootstrap/Control Plane  | https://github.com/rancher/cluster-api-provider-rke2 |
| **Kubeadm**     | Kubeadm                    | Bootstrap/Control Plane  | https://github.com/kubernetes-sigs/cluster-api |
| **AWS**         | CAPA                           | Infrastructure           | https://cluster-api-aws.sigs.k8s.io |
| **Docker**\*    | CAPD                           | Infrastructure           | https://cluster-api.sigs.k8s.io |
| **vSphere**         | CAPV                           | Infrastructure           | https://github.com/kubernetes-sigs/cluster-api-provider-vsphere |
| **Azure** (Only AKS clusters)         | CAPZ                           | Infrastructure           | https://capz.sigs.k8s.io/ |
| **Addon Provider Fleet**    | CAAPF                           | Addon           | http://github.com/rancher-sandbox/cluster-api-addon-provider-fleet |

*Recommended only for development purposes.

## List of providers in experimental mode

This is a list of providers that are in an advanced state of development and will soon become certified.

| Platform        | Code Name                      | Provider Type            | Docs                     |
|-----------------|--------------------------------|--------------------------|--------------------------|
