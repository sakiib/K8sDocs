1. Overview
    * What is Kubernetes?
    * Kubernetes Components
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