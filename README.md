This project is to showcase how to deploy react build on kubernetes

# To run

1. make sure you have a running kubernetes cluster (minikube will work, see [here](https://kubernetes.io/docs/tutorials/hello-minikube/) for details on how to run minikube).

2. run server as pod/service in kube cluster

   ```
   $ kubectl apply -f frontend.yaml
   ```

3. You could verify build is running by going to `<minikube-ip-address>:31000`

References:

1. https://medium.com/@shakyShane/lets-talk-about-docker-artifacts-27454560384f
