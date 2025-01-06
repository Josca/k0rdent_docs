# Welcome to K0rdent Docs

## Introduction

Mirantis K0rdent project is focused on developing a consistent way to deploy 
and manage Kubernetes clusters at scale. Think of K0rdent as a "super 
control plane" designed to manage other Kubernetes control planes. Whether 
you want to manage Kubernetes clusters on-premises, in the cloud, or a
combination of both, K0rdent provides a consistent way to do so. With
full life-cycle management, including provisioning, configuration, and
maintenance, K0rdnet is designed to be a repeatable and secure way 
to manage your Kubernetes clusters in a central location.

## K0rdent vs HMC

K0rdent includes all of the components below, but because HMC was the first
component to be developed, it is still referred to as "HMC" in some documentation.
In many ways "K0rdent" and "HMC" are synonymous.

K0rdent is built around the creation of a set of standardised templates that enable 
easy, repeatable cluster deployments and life cycle management. 

The main components of K0rdent include:

 * **Hybrid Multi-Cluster Controller (HMC)**

    Deployment and life-cycle management of Kubernetes clusters, including configuration, updates, and other CRUD operations.

 * **State Management Controller (SMC)**

    Installation and life-cycle management of [beach-head services](glossary.md#beach-head-services), policy, Kubernetes API configurations and more.

 * **Observability (OBS)**

    Cluster and beach-head services monitoring, events and log management.

## Quick Start

See the [K0rdent Quick Start Guide](quick-start/k0rdent-installation.md)

## Supported Providers

K0rdent leverages the Cluster API provider ecosystem, the following providers have
had `ProviderTemplates` created and validated, and more are in the works.

 * [AWS](quick-start/aws.md)
 * [Azure](quick-start/azure.md)
 * [vSphere](quick-start/vsphere.md)

## Development Documentation

Documentation related to development process and developer specific notes located in
the [main repository](https://github.com/k0rdent/kcm/blob/main/docs/dev.md).
