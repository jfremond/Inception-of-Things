# Inception-of-Things by [bbrassar](https://github.com/benjaminbrassart) and [jfremond](https://github.com/jfremond)
> A 42 system administration project where we're introduced to **Kubernetes**
> using **Vagrant**, **K3s**, **K3d**, and **Argo CD**.

## 📖 Overview
This project is a minimal introduction to Kubernetes. It aims to deepen our
knowledge by making us set up several environments under specific rules using
Vagrant, K3s, K3d and Argo CD.

## 🎯 Objectives
-   Set up virtual machines with **Vagrant**, following modern practices
-   Install and configure **K3s** in controller mode and agent mode to build a
lightweight Kubernetes cluster
-   Use **kubectl** to interact with and inspect the cluster
-   Deploy multiple applications on K3s and route traffic to them based on the
Host header using **Ingress**
-   Understand the difference between **K3s** and **K3d**
-   Install and use **K3d** to run a Kubernetes cluster inside Docker, without
relying on Vagrant
-   Set up **Argo CD** to implement a continuous deployment workflow, syncing an
application automatically from a
[public GitHub repository](https://github.com/jfremond/jfremond-iot)
-   Manage Kubernetes resources across dedicated **namespaces**

## 📚 Lexicon
-   **Kubernetes (K8s)**: Automates the deployment, scaling and
management of containerized applications.
-   **K3s**: Lightweight Kubernetes distribution designed for
resource-constrained environments.
-   **K3d**: Runs K3s inside Docker containers, making it quick and easy to spin
up a Kubernetes server without a virtual machine.
-   **Vagrant**: Builds and manages virtual machine environments through a
configuration file (the `Vagrantfile`).
-   **kubectl**: Lets us interact with a Kubernetes cluster's API from the
command line.
-   **Ingress**: Manages external access to services in a cluster.
-   **Namespace**: Divides cluster resources between multiple users or
applications.
-   **Pod**: The smallest deployable unit in Kubernetes.
-   **Deployment**: Manages a set of identical pods, handling scaling, updates
and rollbacks.
-   **Replica**: Running copy of a pod, used to ensure availability and handle
load.
-   **Argo CD**: Provides a declarative, GitOps continuous delivery tool for
Kubernetes, automatically syncing the cluster's state with configuration stored
in a Git repository.
-   **GitOps**: Uses Git as the single source of truth for declarative
infrastructure and application configuration.
