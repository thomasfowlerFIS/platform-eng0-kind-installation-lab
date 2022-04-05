# Lab - kind Installation and Provisioning

## **Objectives**

1. Install kind (Kubernetes In Docker) locally and initialize a k8s cluster.

1. Understand at a high-level how the Kubernetes architecture is arranged.

1. Identify and map the components/objects observed in your k8s cluster to
their conceptual counterparts.

-------------------------------------------------

### **Requirements**

1. Web browser
1. Terminal
1. KIND installation instructions

-------------------------------------------------

### **Steps**

1. Read and complete the instructions located here:

    [kind Installation Instructions](https://kind.sigs.k8s.io/docs/user/quick-start/#installation)

1. Once kind is installed, follow the remainder of the sections on the page until you finish with the following section:

    [Loading an Image Into Your Cluster](https://kind.sigs.k8s.io/docs/user/quick-start/#loading-an-image-into-your-cluster)

    > _**Note**_: This will serve as a basis for any other container image you may wish to deploy to your kind k8s cluster.

1. Lastly, experiment with the final section:

    [Configuring Your kind Cluster](https://kind.sigs.k8s.io/docs/user/quick-start/#configuring-your-kind-cluster)

**Stretch goals**:

* Experiement with the `kubectl` CLI tool to inspect the various attributes
of your cluster and ask yourself the following questions:

  * What do you see in terms of workloads?
  * Are you able to discern the purpose of some of the components in your
  cluster?
  * What are some additional things you notice about how the various
  workloads are labeled and categorized (think `namespaces`)?

-------------------------------------------------

### **Deliverables**

In order to successfully complete this lab you must:

* Successfully install kind and its associated dependencies.

* Create and initialize a kind k8s cluster.

* Successfully load a custom container image of your own to your
cluster.

-------------------------------------------------
