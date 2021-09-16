# Docker Desktop Kubernetes

Install the Docker Desktop, after enable Kubernetes on its configuration section.

# Ingress

You are going to need to install the ingress-nginx, to do so run that command

```sh
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v0.43.0/deploy/static/provider/cloud/deploy.yaml
```

# Hosts File

For each domain that you set in ingress, you need to put it at the hosts files in `c:\windows\system32\drivers\etc\hosts`

# Dashboard

To install the K8s Dashboard, run that command:

```sh
kubectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v2.2.0/aio/deploy/recommended.yaml
```

# Useful links

https://github.com/docker/for-win/issues/7094

https://kubernetes.io/blog/2020/05/21/wsl-docker-kubernetes-on-the-windows-desktop/

https://github.com/kubernetes-tn/guideline-kubernetes-enterprise/blob/master/general/desktop-env-setup.md

https://stackoverflow.com/questions/60839510/docker-desktop-k8s-plus-https-proxy-multiple-external-ports-to-pods-on-http-in
