# Assignment-3-Build-a-Voting-App-on-Kubernetes
Assignment #3: Build a Voting App on Kubernetes


    5  Set-Alias -Name k -Value kubectl
    6  alias k='kubectl'
    7  source ~/.bashrc
    8  k version
    9  nano ~/.bashrc
   10  vi voting-app-deployment.yaml
   11  k apply -f voting-app-deployment.yaml
   12  vi voting-app-service.yaml
   13  kubectl apply -f voting-app-service.yaml
   14  k get deployments
   15  kubectl get services
   16  vi redis-deployment.yaml
   17  kubectl apply -f redis-deployment.yaml
   18  vi redis-service.yaml
   19  kubectl apply -f redis-service.yaml
   20  kubectl get deployments
   21  kubectl get services
   22   vi worker-deployment.yaml
   23  kubectl apply -f worker-deployment.yaml
   24  vi worker-service.yaml
   25  kubectl apply -f worker-service.yaml
   26  kubectl get deployments
   27  kubectl get services
   28  vi db-deployment.yaml
   29  kubectl apply -f db-deployment.yaml
   30  vi db-service.yaml
   31  kubectl apply -f db-service.yaml
   32  kubectl get deployments
   33  kubectl get services
   34  vi result-app-deployment.yaml
   35  kubectl apply -f result-app-deployment.yaml
   36  vi result-app-service.yaml
   37  kubectl apply -f result-app-service.yaml
   38  kubectl get deployments
   39  kubectl get services
   40  history
Voting App: http://18.221.95.100:30000
Result App: http://18.221.95.100:30001


