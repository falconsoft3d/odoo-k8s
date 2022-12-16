# odoo-k8s

````
git clone https://github.com/falconsoft3d/odoo-k8s.git
cd odoo-k8s/minikube
````

# minikube
````
$ kubectl apply -f 1.yaml
$ kubectl apply -f 2.yaml
$ kubectl apply -f 3.yaml
$ kubectl apply -f 4.yaml
$ kubectl apply -f 5.yaml
$ kubectl apply -f 6.yaml
````


````
kubectl config set-context --current --namespace=default
kubectl config set-context --current --namespace=odoo
````

````
kubectl delete namespace odoo 
````
