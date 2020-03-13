## Setup local Kubernetes with Kubeadm:
https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/create-cluster-kubeadm/

## Access Kubernetes cluster from a client machine:
1. From master node: scp /etc/kubernetes/admin.conf username@client-machine-ip:~/.kube/config
2. Verify access by kubectl: kubectl get pods

## More Information
https://rancher.com/learning-paths/how-to-manage-kubernetes-with-kubectl/