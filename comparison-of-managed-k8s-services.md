---
id: 5i57pfvasv0vp99g37ar9ai
title: Comparison of Managed Kubernetes Services
desc: ''
updated: 1679333550587
created: 1679073696430
---

Systematic comparison along a number of well-defined dimensions of the following managed Kubernetes services:

- EKS
- GKE
- AKS
- LKE (Linode)

## Content

### Dimensions that can be used for the comparison

- Compared solutions
    - [Linode Kubernetes Engine (LKE)](https://www.linode.com/products/kubernetes/)
    - [Amazon Elastic Kubernetes Service (EKS)](https://aws.amazon.com/eks/)
    - [Google Kubernetes Engine (GKE)](https://cloud.google.com/kubernetes-engine)
    - [Azure Kubernetes Service (AKS)](https://azure.microsoft.com/services/kubernetes-service/)
- Characteristics
    - Year introduced
    - General description
- Latest/available Kubernetes versions
- Kubernetes updates
    - Componets on master nodes? Components on worker nodes?
    - Automatic? On-demand?
    - How frequently?
- Global distribution
    - In how many regions around the world it's available?
- Control plane availability 
    - How many master nodes? Distributed across zones/regions?
    - SLA for control plane?
    - Backups: is etcd automatically backed up? How frequently?
- Integrations with other services of the cloud provider
    - Monitoring
    - Logging
    - Volume provisioning (StorageClass)
    - Load balancer provisioning  (LoadBalancer Service)
    - Node provisioning (Cluster Autoscaler)
- Limits
    - Nodes per cluster
    - Pods per node
- Security
    - Built-in NetworkPolicy support?
    - Built-in PodSecurityPolicy support?
- Usability
    - CLI (how many commands, and options per command, to get a cluster running?)
    - GUI (how many clicks and parameter settings to get a cluster running?)
    - Include obtaining of kubeconfig file on local machine
- Pricing
    - Pricing structure (cost for control plane or only for other cloud resources?)
    - Cost of an example cluster
- Peformance
    - Time to create an eample cluster (average over multiple regions)
    - Time to deploy an example application

### Existing comparisons

#### https://logz.io/blog/kubernetes-as-a-service-gke-aks-eks/

_Jun 11th, 2019_

- ~Current Kubernetes version~
- ~Updates (Kubernetes version on control plane and worker nodes)~
- ~Integrated monitoring solutions~
- ~Global availability~
- ~Cluster autoscaler support~
- ~High availability of control plane~
- Popularity (Google searches and StackOverflow posts)
- ~Pricing structure~

#### https://platform9.com/blog/kubernetes-cloud-services-comparing-gke-eks-and-aks/

_January 6, 2020_

- ~Pricing structure~
- ~Current Kubernetes version~
- ~Global availability~
- ~Upgrades (Kubernetes version on control plane and worker nodes)~
- Node groups
- ~Integrated monitoring solutions~
- ~SLA~
- ~Nodes per cluster~

#### https://www.stackrox.com/post/2020/02/eks-vs-gke-vs-aks/

_Feb 10, 2020_

- ~Current Kubernetes version~
- ~Upgrades (on master and worker nodes)~
- Container runtime choices
- ~Control plane high availability~
- ~Control plane SLA~
- ~Pricing structure~
- ~Integrated logging solutions~
- ~Integrated monitoriong solutions~
- ~Nodes per cluster~
- ~Pods per nodes~
- CNI plugin choices 
- ~NetworkPolicy support~
- ~PodSecurityPolicy support~

#### https://kubedex.com/google-gke-vs-microsoft-aks-vs-amazon-eks/

_December 29, 2018_

- ~Current Kubernetes version~
- ~Global availability~
- ~Control plane high availability~
- ~Cluster creation time~
- ~SLA~
- ~Pricing structure~
- Container runtime choices
- ~Pods per node~
- ~Nodes per cluster~
- ~Cluster autoscaling support~
- ~Kubernetes upgrades~
- ~Integrated logging solutions~
- ~Integrated monitoring solutions~
- ~NetworkPolicy support~

#### https://blog.alcide.io/kubernetes-as-a-service-eks-vs.-aks-vs.-gke

_May 4, 2020_

- ~Current Kubernetes version~
- ~Upgrades (control plane and worker nodes)~
- Container runtime choices
- ~NetworkPolicy support~
- ~PodSecurityPolicy support~
- ~SLA~
- ~Cluster creation time~
- ~Pricing structure~

#### https://medium.com/faun/which-cloud-provider-is-best-for-managed-kubernetes-7de56f468a27

_March 11, 2020_

- ~Current Kubernetes version~
- ~Cluster creation time~
- ~Time to provision an application~
- ~Cost for an example cluster~
- Ease of use

#### https://medium.com/@jaychapel/managed-kubernetes-pricing-comparison-eks-vs-aks-vs-gke-dbf3f2c6290c

_Apr 7, 2020_

- ~Pricing comparison of example cluster (80 CPUs, 320 GB RAM)~

## Remarks

## Resources

1. [[1.article-ideas.comparison-of-managed-k8s-services.dimensions]]: analysis for the comparison dimensions