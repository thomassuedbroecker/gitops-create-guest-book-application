# gitops-create-hello-world-application

The objective is to show how to deploy a hello world application to an existing customer using the bootstrap configuration of Argo CD from Software Everywhere.

## Pre-requisites

Follow [lab 3 of Software Everywhere](https://operate.cloudnativetoolkit.dev/getting-started/lab3/) to setup a OpenShift Cluster preconfigure with Argo CD and an bootstrap configuration.

## Bootstrap configuration

The bootstrap configuration that was created from the [terraform-tools-gitops](https://github.com/cloud-native-toolkit/terraform-tools-gitops) module has following structure.

![](https://github.com/cloud-native-toolkit/terraform-tools-gitops/blob/main/template/docs/gitops-structure-overview.png)

The diagram is provided by the terraform-tools-gitops]

We will save a new `Argo CD application configuration` in the `2-Application` folder in your created bootstrap repository.

![](images/gitops-argocd-config-01.png)

![](images/gitops-argocd-config-02.png)

## Create a new Argo CD configuration





