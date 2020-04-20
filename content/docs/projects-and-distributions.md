+++
title = "Projects and Distributions"
weight = "3"
+++

Cloud Foundry is a large, open-source project. All of the source code available on GitHub. There are a few different organizations:

- https://github.com/cloudfoundry: Core Cloud Foundry projects and components include all source code and documentation.
- https://github.com/cloudfoundry-incubator: Projects under development that are not yet part of the core Cloud Foundry project. The incubator serves as a proving ground. Projects typically graduate to the core Cloud Foundry project or are shuttered.
- https://github.com/cloudfoundry-community: Community-contributed and maintained projects outside of, but related to, the core Cloud Foundry project.
- https://github.com/cloudfoundry-tutotials: The organization that houses this and other tutorials.
- https://github.com/cloudfoundry-attic: Old projects no longer actively developed.

Cloud Foundry is a large project with many different components and projects. From these projects, there are many interoperable distributions available for end-users. While these distributions may differ in approach and alterations, they all support the same common-core, ensuring interoperability across all Cloud Foundry distributions.

## Open Source Cloud Foundry Distributions

There are three major open source distributions under development:

1. [Cloud Foundry](https://github.com/cloudfoundry/cf-deployment) deployed by [BOSH](https://bosh.io): This is the oldest and most widely used distribution whereby Cloud Foundry components are deployed on Virtual Machines on any infrastructure as a service.  
1. [KubeCF](https://github.com/cloudfoundry-incubator/kubecf): An incubating distribution whereby Cloud Foundry components are deployed as pods to a Kubernetes cluster. This distribution uses the [cf-operator](https://github.com/cloudfoundry-incubator/cf-operator) to containerize the same BOSH releases above for deployment on Kubernetes.
1. [CF for K8s](https://github.com/cloudfoundry/cf-for-k8s): An experimental project leveraging native Kubernetes components to implement the Cloud Foundry functionality.

## Commercial Cloud Foundry Distributions

There are many commercial distributions of Cloud Foundry available for purchase. The Cloud Foundry Foundation maintains a certification program for commercial distributions to ensure consistency of functionality, APIs, and experiences across commercial distributions. A list of [certified distributions](https://www.cloudfoundry.org/certified-platforms/) is available [here](https://www.cloudfoundry.org/certified-platforms/).
