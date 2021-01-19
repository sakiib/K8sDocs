1. Overview
    * What is Kubernetes?
  Kubernetes is an open source container orchaestrations tool which is portable, extensible and facilitates both declarative configuration and automation. 
  **Things to know here:** Traditional deployment era, Virtualized deployment era, Container deployment, why you need K8s and what it can do for you, what K8s is not.
    * Kubernetes Components
  Whay you deploy Kubernetes, you get a cluster. A Kubernetes cluster consists of a set of worker machines, called nodes, that run containerized applications. Every cluster has at least one worker node. The worker node(s) host the Pods that are the components of the application workload. The control plane manages the worker nodes and the pods in the cluster. 
  Control plane's components make global decisions about the cluster(for example, scheduling), as well as detecting and responding to cluster events(for example, starting up a new pod when a deployment's replicas field is unsatisfied).
  **Control Plane Components:** 
  *kube-apiserver:* It exposes the K8s API. It's the front end for the K8s control plane. It's designed to scale horizontally-that is, it scales by deploying more instances. 
  *etcd:* Consistent and highly-available key value store used as K8s backing store for all cluster data.
  *kube-scheduler:* Watches for newly created pods with no assigned node, and selects a node for them to run on (considering factors: resource requiremtns, deadlines etc).
  *kube-controller-manager:* It runs controller processes. It inclused Node controller, replication controller, endpoints controller, service account and token controllers.
  *cloud-controller-manager:* It embeds cloud-specific control logic. 
  **Node Components:** 
  *kubelet:* Runs of each node in the cluster & makes sure that containers are running in a pod.
  *kube-proxy:* a network proxy that runs on each node in your cluster, implementing part of the K8s service concept.
  *container runtime:* a software that is responsible for running containers.
    * The Kubernetes API
    * Working with Kubernetes Objects
        * Understanding Kubernetes Objects
        * Kubernetes Object Management
        * Object Names and IDs
        * Namespaces
        * Labels and Selectors
        * Annotations
        * Field Selectors
        * Recommended Labels

2. Cluster Architecture
    * Nodes
    * Control Panel-Node Communication
    * Controllers
    * Cloud Controller Manager

3. Containers
    * Images
    * Container Environments
    * Runtime Class
    * Container Lifecycle Hooks

4. Workloads
    * Pods
        * Pod Lifecycle
        * Init Containers
        * Pod Topology Spread Constraints
        * Disruptions
        * Ephemeral Containers
    * Workload Resources
        * Deployments
        * ReplicaSet
        * StatefulSets
        * DaemonSet
        * Jobs
        * Garbage Collection
        * TTL Controller for Finished Resources
        * CronJob
        * ReplicationController

5. Services, Load Balancing, and Networking
    * Service
    * Service Topology
    * DNS for Services and Pods
    * Connecting Applications with Services
    * EndpointSlices
    * Ingress
    * Ingress Controllers
    * Network Policies
    * Adding entries to Pod /etc/hosts with HostAliases
    * IPv4/IPv6 dual-stack

6. Storage
    * Volumes
    * Persistent Volumes
    * Volume Snapshots
    * CSI Volume Cloning
    * Storage Classes
    * Volume Snapshot Classes
    * Dynamic Volume Provisioning
    * Storage Capacity
    * Ephemeral Volumes
    * Node-specific Volume Limits

7. Configuration
    * Configuration Best Practices
    * ConfigMaps
    * Secrets
    * Managing Resources for Containers
    * Organizing Cluster Access Using kubeconfig Files
    * Pod Priority and Preemption

8. Security
    * Overview of Cloud Native Security
    * Pod Security Standards
    * Controlling Access to the Kubernetes API