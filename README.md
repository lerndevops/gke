## GKE overview
> Google Kubernetes Engine (GKE) provides a managed environment for deploying, managing, and scaling your containerized applications using Google infrastructure. The GKE environment consists of multiple machines (specifically, Compute Engine instances) grouped together to form a cluster.

## Cluster orchestration with GKE
* GKE clusters are powered by the **`Kubernetes`** open source cluster management system. 
* Kubernetes provides the mechanisms through which you interact with your cluster. 
* You use Kubernetes commands and resources to deploy and manage your applications, perform administration tasks, set policies, and monitor the health of your deployed workloads.

## GKE Modes of operation
> The level of flexibility, responsibility, and control that you require for your clusters determines the mode of operation to use in GKE. GKE clusters have two modes of operation to choose from:

* **`Autopilot:`** Manages the entire cluster and node infrastructure for you. Autopilot provides a hands-off Kubernetes experience so that you can focus on your workloads and only pay for the resources required to run your applications. Autopilot clusters are pre-configured with an optimized cluster configuration that is ready for production workloads.

* **`Standard:`** Provides you with node configuration flexibility and full control over managing your clusters and node infrastructure. For clusters created using the Standard mode, you determine the configurations needed for your production workloads, and you pay for the nodes that you use.

## Kubernetes on Google Cloud
> When you run a GKE cluster, you also gain the benefit of advanced cluster management features that Google Cloud provides. These include:

Google Cloud's 
* [load-balancing](https://cloud.google.com/compute/docs/load-balancing-and-autoscaling) for Compute Engine instances
* [Node pools](https://cloud.google.com/kubernetes-engine/docs/concepts/node-pools) to designate subsets of nodes within a cluster for additional flexibility
* [Automatic scaling](https://cloud.google.com/kubernetes-engine/docs/concepts/cluster-autoscaler) of your cluster's node instance count
* [Automatic upgrades](https://cloud.google.com/kubernetes-engine/docs/how-to/node-auto-upgrades) for your cluster's node software
* [Node auto-repair](https://cloud.google.com/kubernetes-engine/docs/how-to/node-auto-repair) to maintain node health and availability
* [Logging and monitoring](https://cloud.google.com/stackdriver/docs/solutions/gke) with Google Cloud's operations suite for visibility into your cluster

## Thinking About Production GKE Setup?

> [Best Practices for operating Containers](https://cloud.google.com/architecture/best-practices-for-operating-containers)

> [Preparing GKE Environment for Production](https://cloud.google.com/architecture/prep-kubernetes-engine-for-prod)

> GKE SLA 
**https://cloud.google.com/kubernetes-engine/sla**

> GKE Pricing
**https://cloud.google.com/kubernetes-engine/pricing**

> Quotas & Limits 
**https://cloud.google.com/kubernetes-engine/quotas** 

> Complaince 
**https://cloud.google.com/security/compliance**
