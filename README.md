# ansible-kubeadm

## create nfs

```console
ansible-playbook k8s-nfs-playbook.yml
```

## create control-plane

```console
ansible-playbook k8s-controlplane-playbook.yml
```

## create nodes

```console
ansible-playbook k8s-node-playbook.yml
```

## setup helm

```console
ansible-playbook k8s-helm-playbook.yml
```
