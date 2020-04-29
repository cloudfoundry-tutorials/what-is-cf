+++
title = "Projects and Distributions"
weight = "3"
+++

Cloud Foundry is a large, open-source project. All of the source code available on GitHub. There are a few different organizations:

- [https://github.com/cloudfoundry](https://github.com/cloudfoundry): Core Cloud Foundry projects and components include all source code and documentation.
- [https://github.com/cloudfoundry-incubator](https://github.com/cloudfoundry-incubator): Projects under development that are not yet part of the core Cloud Foundry project. The incubator serves as a proving ground. Projects typically graduate to the core Cloud Foundry project or are shuttered.
- [https://github.com/paketo-buildpacks](https://github.com/paketo-buildpacks): A collection of Cloud Native [Buildpacks](https://buildpacks.io) designed for Cloud Foundry and/or Kubernetes.
- [https://github.com/cloudfoundry-community](https://github.com/cloudfoundry-community): Community-contributed and maintained projects outside of, but related to, the core Cloud Foundry project.
- [https://github.com/cloudfoundry-tutorials](https://github.com/cloudfoundry-tutorials): The organization that houses this and other tutorials.

Cloud Foundry is a large project with many different components and projects. From these projects, there are many interoperable distributions available for end-users. While these distributions may differ in approach and alterations, they all support the same common-core, ensuring interoperability across all Cloud Foundry distributions.

## Open Source Distributions

There are three major open source distributions under development:

1. [Cloud Foundry](https://github.com/cloudfoundry/cf-deployment) deployed by [BOSH](https://bosh.io): This is the oldest and most widely used distribution whereby Cloud Foundry components are deployed on Virtual Machines on any infrastructure as a service.  
1. [KubeCF](https://github.com/cloudfoundry-incubator/kubecf): Currently the most widely-adopted Cloud Foundry distribution available for Kubernetes that you can install yourself. This distribution uses the [cf-operator](https://github.com/cloudfoundry-incubator/cf-operator) to containerize the same BOSH releases above for deployment on Kubernetes.
1. [CF for K8s](https://github.com/cloudfoundry/cf-for-k8s): An on-going project that is repackaging Cloud Foundry for Kubernetes, and also switching some internal components for more Kubernetes-native equivalents. At the time of writing it is not ready for production use, but is making great progress.

## Where is Cloud Foundry?

The open source distributions of Cloud Foundry can be run standalone or packaged inside commercial offerings. Your company, or even your government, may be running Cloud Foundry and you don't even know it. Cloud Foundry is running production workloads in over half of the Fortune 500 companies.

Some offerings denote it in the name, like IBM Cloud Foundry or Atos Cloud Foundry. But Cloud Foundry is also at the core of VMWare's Tanzu Application Service, SUSE Cloud Application Platform, SAP Cloud Platform, and Cloud.gov. This list is by no means exhaustive. There are additional as-a-service offerings widely available and installations of Cloud Foundry in many enterprises and governments worldwide. 
