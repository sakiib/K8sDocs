1. Introducing Kubernetes
    * Understanding the need for a system like Kubernetes
      * Moving from monolithic apps to microservices
      * Providing a consistent environment to applications
      * Moving to continuous delivery: DevOps & NoOps
    * Introducing container technologies
      * Understanding what containers are
      * Introducing to Docker container platform
      * Introducing to rkt-an alternative to Docker
    * Introducing Kubernetes
      * Understanding its origins
      * Looking at Kubernetes from the top of a mountain
      * Understanding the architecture of a Kubernetes cluster
      * Running an application in Kubernetes
      * Understanding the benefits of using Kubernetes
2. First steps with Docker and Kubernetes
    * Creating, running, and sharing a container image
      * Installing Docker and running a Hello World container
      * Creating a trivial app
      * Creating a Dockerfile for the image
      * Building the container imager
      * Exploring inside of a running container
      * Stopping and removing a container
      * Pushing the image to an image registry
    * Setting up a Kubernetes cluster
      * Running a local single-node Kubernetes cluster with Minikube
      * Using a hosted Kubernetes cluster with Google Kubernetes Engine
      * Setting up and alias and command-line completion for kubectl
    * Running your first app on Kubernetes
      * Deploying your simple app
      * Accessing your web application
      * The logical part of your system
      * Horizontally scaling the application
      * Examining what nodes your app is running on
      * Introducing the Kuberentes dashboard
3. Pods: running containers in Kubernetes
    * Introducing pods
      * Understanding why we need pods
      * Understanding pods
      * Organizing containers across pods properly
    * Creating pods from YAML or JSON descriptiors
      * Examining a YAML descroptor of an existing pod
      * Creating a simple YAML descriptor for a pod
      * Using kubectl create to create the pod
      * Viewing application logs
      * Sending requests to the pod
    * Organizing pods with labels
      * Introducing labels
      * Specifying labels when creating a pod
      * Modifying labels of existing pods
    * Listing subsets of pods through lable selectors
      * Listing pods using a label selector 
      * Using multiple conditions in a label selector
    * Using labels and selectors to constrain pod scheduling
      * Using labels for categorizing worker nodes
      * Scheduling pods to specific nodes
      * Scheduling to one specific node
    * Annotating pods
      * Looking up an object's annotations
      * Adding and modifying annotations
    * Using namespaces to group resources
      * Understanding the need for namespaces
      * Descovering other namespaes and their pods
      * Creating a namespace
      * Managing objects in other namespaces
      * Understanding the isolation provided by namespaces
    * Stopping and removing pods
      * Deleting a pod by name
      * Deleting pods using label selectors
      * Deleting pods by deleting the whole namespace
      * Deleting all pods in a namespace, while keeping the namespace
      * Deleteing (almost) all resources in a namespace