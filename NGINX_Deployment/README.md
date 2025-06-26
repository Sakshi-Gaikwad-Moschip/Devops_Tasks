Task:
Deploy an NGINX web server using a Kubernetes Deployment with 2 replicas, and expose it using a Service of type NodePort.
Objectives:
Set up a local Kubernetes cluster (Eg. Minikube)
Create a Deployment running the nginx image with 2 replicas.
Expose the Deployment using a Service (NodePort) so it can be accessed externally.
Verify that both pods are running (using Commands)
Access the NGINX welcome page via browser or curl
Output: Share the Pods running Status and Nginx page! 

commands:

    1. kubectl apply -f nginx-deployment.yaml

    2. kubectl get pods

    3. kubectl apply -f nginx-service.yaml

    4. kubectl get svc

    5. minicube service nginx-deployment

    6. curl http://<ip>:<node port>