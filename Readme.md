## Mongodb and mongo-express service maintained in kubernetes

This repository helps in setting up a mongodb database with mongo express as the GUI on Kubernetes.

How to use kubernetes in a local environment:

- **Minikube**: Installing using the link [here](https://minikube.sigs.k8s.io/docs/start/]).
- Install docker, kubectl, kubeadm and kubelet
  `$sudo apt install docker kubectl kubeadm kubelet`

The system architecture:

[system_design](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/5af3325d-50ef-4d98-bed6-ef6d2fc080ce/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221108%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221108T142053Z&X-Amz-Expires=86400&X-Amz-Signature=a13c2099dbd73f58a5116a3b0f440647a1f00211f017c0e99bcc87a01a318750&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22Untitled.png%22&x-id=GetObject)
