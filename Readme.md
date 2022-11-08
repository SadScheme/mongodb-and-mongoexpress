## Mongodb and mongo-express service maintained in kubernetes

This repository helps in setting up a mongodb database with mongo express as the GUI on Kubernetes.

How to use kubernetes in a local environment:

- **Minikube**: Installing using the link [here](https://minikube.sigs.k8s.io/docs/start/]).
- Install docker, kubectl, kubeadm and kubelet
  `$sudo apt install docker kubectl kubeadm kubelet`

The system architecture

![system_design](./image/system_design.png)

Flow Design

![flow](./image/flow.png)
