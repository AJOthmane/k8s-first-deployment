## Commands to deploy this mini web app
1. kubectl apply -f mongo-config.yaml : to execute the configuration
2. kubectl apply -f mongo-secret.yaml : to execute the secret
3. kubectl apply -f mongo.yaml : to create the monogodb service and deploy it
4. kubectl apply -f webapp.yaml : to create the webapp service and deploy it
5. kubectl get srv : to get the port 
6. minikube ip : to get the ip or whenever you're usign k8s from  
7. and from a web broswer go to : ip:port