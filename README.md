Project code for tutorial on how to develop a Node.js/MongoDB application using Docker Compose: https://www.digitalocean.com/community/tutorials/containerizing-a-node-js-application-for-development-with-docker-compose



```
kubectl create -f app-network-networkpolicy.yaml,db-deployment.yaml,db-service.yaml,dbdata-persistentvolumeclaim.yaml,env-configmap.yaml,nodejs-deployment.yaml,nodejs-service.yaml,secret.yaml
```