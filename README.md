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


# Assignment-3-Build-a-Voting-App-on-Kubernetes

**Assignment #3: Build a Voting App on Kubernetes**

Below are the steps involved in setting up the environment and deploying the Voting App on Kubernetes.

```plaintext
 5. Set-Alias -Name k -Value kubectl  # PowerShell-specific
 6. alias k='kubectl'                 # Bash/Zsh
 7. source ~/.bashrc                  # Reload bash profile, Bash-specific
 8. k version                         # Test the alias
 9. nano ~/.bashrc                    # Edit bash profile in nano editor
10. vi voting-app-deployment.yaml     # Edit the voting app deployment file
11. k apply -f voting-app-deployment.yaml  # Apply the deployment
12. vi voting-app-service.yaml       # Edit the voting app service file
13. kubectl apply -f voting-app-service.yaml # Apply the service
14. k get deployments                # List deployments to check status
15. kubectl get services             # List services to check status
16. vi redis-deployment.yaml         # Edit the Redis deployment file
17. kubectl apply -f redis-deployment.yaml  # Apply the Redis deployment
18. vi redis-service.yaml            # Edit the Redis service file
19. kubectl apply -f redis-service.yaml     # Apply the Redis service
20. kubectl get deployments          # List deployments to check status
21. kubectl get services             # List services to check status
22. vi worker-deployment.yaml        # Edit the worker deployment file
23. kubectl apply -f worker-deployment.yaml # Apply the worker deployment
24. vi worker-service.yaml           # Edit the worker service file
25. kubectl apply -f worker-service.yaml    # Apply the worker service
26. kubectl get deployments          # List deployments to check status
27. kubectl get services             # List services to check status
28. vi db-deployment.yaml            # Edit the database deployment file
29. kubectl apply -f db-deployment.yaml     # Apply the database deployment
30. vi db-service.yaml               # Edit the database service file
31. kubectl apply -f db-service.yaml        # Apply the database service
32. kubectl get deployments          # List deployments to check status
33. kubectl get services             # List services to check status
34. vi result-app-deployment.yaml    # Edit the result app deployment file
35. kubectl apply -f result-app-deployment.yaml  # Apply the result app deployment
36. vi result-app-service.yaml       # Edit the result app service file
37. kubectl apply -f result-app-service.yaml    # Apply the result app service
38. kubectl get deployments          # List deployments to check status
39. kubectl get services             # List services to check status
40. history                          # View command 

Access the applications:

Voting App: http://18.221.95.100:30000
Result App: http://18.221.95.100:30001