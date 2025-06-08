# need to create 4 k8s config files:

1. configmap = for mongodb endpoint
2. secret = for mongodb credentials
3. deployment & servive = for mongodb application with internal service
4. deployment & service = for our webapp with external service

# CMDS

- Minikube is just for start-up / delete a cluster
- Kubectl CLI is for configuring the cluster

1. minikube start –driver docker
2. minikube status
3. kubectl get node
4. kubectl get pod
5. kubectl apply -f mongo-config.yml
6. kubectl apply -f mongo-secret.yml
7. kubectl apply -f mongo.yml
8. kubectl apply -f webapp.yml
9. kubectl get all
10. kubectl get configmap
11. kubectl get secret
12. kubectl describe <resourceType> <resourceName>
13. kubectl describe pod <podName>
14. kubectl logs <podName>
