

# ingress install

* install the ingress
* modify the ingress service to be nodeport insteadof loadbalancer

helm install --namespace kube-system nginx ingress-nginx --repo https://kubernetes.github.io/ingress-nginx

kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v0.41.2/deploy/static/provider/cloud/deploy.yaml

kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v0.43.0/deploy/static/provider/cloud/deploy.yaml

helm install --namespace kube-system nginx ingress-nginx --repo https://kubernetes.github.io/ingress-nginx

https://github.com/docker/for-win/issues/7094

https://kubernetes.io/blog/2020/05/21/wsl-docker-kubernetes-on-the-windows-desktop/


kubectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v2.2.0/aio/deploy/recommended.yaml

https://github.com/kubernetes-tn/guideline-kubernetes-enterprise/blob/master/general/desktop-env-setup.md


https://stackoverflow.com/questions/60839510/docker-desktop-k8s-plus-https-proxy-multiple-external-ports-to-pods-on-http-in
