Everything here assumes the namespace `monitoring` exists. I did not write all of these.

On a fresh Kubernetes cluster, you should be able to just kubectl create every manifest here, besides things in the prometheus-operator namespace (Pick manifests with/without cert-manager/storage)
