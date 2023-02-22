# Kubernetes 
0. Introduction and Course Overview
1. Gitlab Repository for the course
2. Join Course Community

## 1 - Kubernetes Core Concepts
1. Introduction to Kubernetes
2. Main Kubernetes Components
3. Kubernetes Architecture (Control Plane and Worker Nodes)
4. Manage Kubernetes Resources - kubectl and config file
5. K8s Configuration File
6. Pre-Requisite: YAML Basics

## 2 - Build Kubernetes Cluster from Scratch
1. Section Introduction and Background Story
2. Kubernetes Cluster Installation Steps
3. Configure K8s Nodes
4. Container Runtime Interface
5. Install Container Runtime (Containerd)
6. Install kubeadm, kubelet and kubectl
7. Initialize Cluster with kubeadm
8. Connect to cluster (kubeconfig & kubectl)
9. Organize Resources with Namespaces 
10. kube-system namespace
11. Pre-Requisite: Networking Basics
12. Networking in K8s - Overview 
13. Container Communication
14. Container Network Interface - CNI
15. Configure Network Plugin - WeaveNet
16. Join Worker Nodes to cluster

## 3 - Deployment, Services & DNS in Kubernetes (Deploy Applications)
1. Section Overview
2. Deploy nginx
3. Create nginx Service
4. Labelling Components
5. Scaling Deployments & Record Kubectl Commands
6. Connect to nginx Pod
7. Why DNS?
8. Pre-Requisite: Domain Name System (DNS)
9. DNS in Kubernetes
10. Configure Service IP Address 
11. Pro Tip for kubectl

## 4 - External Services & Ingress Controller (Access from Outside)
1. Section Overview
2. NodePort
3. Loadbalancer
4. Ingress
5. Setup Ingress - Overview
6. Helm - Package Manager
7. Deploy Ingress Controller
8. Configure Routing

## 5 - Control Access with Users & Permissions
1. Section Introduction
2. Authorization with Role Based Access Control (RBAC)
3. Other Authorization Modes
4. Certificates in Kubernetes
5. Certificates API
6. Demo Overview - Users & Permissions
7. Create User Account
8. Connect to Cluster with User
9. Give User Permission - ClusterRole
10. Create ServiceAccount & Permissions

## 6 - Troubleshooting
1. Section Intro
2. Troubleshoot Applications
3. Debug with temporary Pods
4. Kubectl Format Output
5. Troubleshoot Kubelet and Kubectl Issues

## 7 - Multi Container Pods
1. Section Introduction 
2. Sidcar and Init Containers
3. Demo: Deploy Sidecar and Init Container
4. Exposing Pod Information

## 8 - Persist Data in Kubernetes (Volumes)
1. Section Introduction
2. Persisting Data with Volumes - PV, PVC, SC
3. Configure HostPath Volume
4. Configure emptyDir Volume

## 9 - External Configuration with ConfigMap and Secret
1. Introduction to ConfigMap and Secret
2. Demo: Pass as Environment Variables
3. Demo: Pass as Volumes

## 10 - Resource Requests & Limits
1. Section Introduction
2. What are Resource Requests and Limits
3. Demo: Configure Resource Requests and LImits


## 11 - Scheduling Pods
1. Section Introduction
2. NodeName and Node Selector - Assigning Pods to Nodes
3. Node Affinity - Assigning Pods to Nodes
4. Taints & Tolerations
5. Inter-Pod Affinity

## 12 - Health Checks with Liveness and Readiness Probes
1. Section Introduction
2. What are Liveness and Readiness Probes
3. Configure Liveness and Readiness Probes

## 13 - Deployment Strategies - Rolling Update
1. Section Introduction
2. What is a ReplicaSet
3. Deployment Update Strategies - Rolling Update

## 14 - ETCD Backup & Restore
1. Section Introduction
2. What etcd stores
3. Backing up etcd store
4. Alternatives to manage etcd
5. Restoring etcd 

## 15 - Kubernetes REST API
1. Section Introduction
2. Access REST API with kubectl proxy
3. Interacting with REST API (without kubectl proxy)

## 16 - Upgrade K8s Cluster
1. Section Introduction
2. How Cluster Upgrade works
3. Demo: Upgrade Cluster

## 17 - Manage multiple Clusters with Kube Contexts
1. Section Introduction
2. Working with multiple clusters using Kube Contexts

## 18 - Certificate Management in Kubernetes
1. Section Introduction
2. Check Certificate Expiration
3. Renew Certificates

## 19 - Secure Cluster - Control Traffic with Network Policies
1. Section Introduction
2. How Network Policies work
3. Configure Network Policies for Cluster

## 20 - CKA Exam Tips
1. Section Introduction
2. Exam Tips
3. Tips during exam
4. Practice with Mock Exams
5. Official Exam Resources

Congratulations! :)

More Resources
