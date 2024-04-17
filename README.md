These files Consists of Yaml code of Config and secret which is needed to deploy a Mern App with the Help of Kubernetes,
If you Find It Useful Then Don't forget to give a star...
Here is the Few commands you need while deploying the App:-
------------------------------------------------------------
minikube start
--------------
kubectl get pod
---------------
kubectl apply -f mongo-config.yaml
----------------------------------
kubectl apply -f secret.yaml
----------------------------------
kubectl apply -f mongo-app.yaml
----------------------------------
kubectl apply -f web-app.yaml
----------------------------------
kubectl get pod
----------------------------------
kubectl get configmap
----------------------------------
kubectl get secret
----------------------------------
kubectl get svc
---------------------------------
minikube ip
----------------------------------
kubectl get node -o wide


