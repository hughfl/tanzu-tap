# tanzu-tap

Prerequisites

1.  A Tanzu Network account with pivnet installed - This guide walks you through setting up your account on the Tanzu Network, as well as installing the pivnet CLI tool.
2.  The tanzu CLI installed and configured - This guide walks you through downloading, installing, and using the tanzu CLI tool.
3.  You have a Kubernetes cluster created and ready - In this guide I am using a GKE cluster, but most major Kubernetes cluster providers should work. Make sure you kubectl context is pointed to this cluster. Cluster and resource requirements can be found here.
4.  A Docker Hub account - Other repositories are supported, but for ease of use and configuration, this guide uses Docker Hub.

***Optional: A custom domain - In this guide you will just use your /etc/hosts file to handle routing. However, you may decide you want to set up DNS routing and records to access your install. More on this later in this guide.
