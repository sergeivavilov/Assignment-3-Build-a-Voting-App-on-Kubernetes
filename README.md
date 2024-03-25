# Assignment-3-Build-a-Voting-App-on-Kubernetes

**Assignment #3: Build a Voting App on Kubernetes**

Below are the steps involved in setting up the environment and deploying the Voting App on Kubernetes.

```plaintext
1. Set-Alias -Name k -Value kubectl  # PowerShell-specific
2. alias k='kubectl'                 # Bash/Zsh
3. source ~/.bashrc                  # Reload bash profile, Bash-specific
4. k version                         # Test the alias
5. nano ~/.bashrc                    # Edit bash profile in nano editor
6. vi voting-app-deployment.yaml     # Edit the voting app deployment file
7. k apply -f voting-app-deployment.yaml  # Apply the deployment
8. vi voting-app-service.yaml        # Edit the voting app service file
9. kubectl apply -f voting-app-service.yaml # Apply the service
10. k get deployments                # List deployments to check status
11. kubectl get services             # List services to check status
12. vi redis-deployment.yaml         # Edit the Redis deployment file
13. kubectl apply -f redis-deployment.yaml  # Apply the Redis deployment
14. vi redis-service.yaml            # Edit the Redis service file
15. kubectl apply -f redis-service.yaml     # Apply the Redis service
16. kubectl get deployments          # List deployments to check status
17. kubectl get services             # List services to check status
18. vi worker-deployment.yaml        # Edit the worker deployment file
19. kubectl apply -f worker-deployment.yaml # Apply the worker deployment
20. vi worker-service.yaml           # Edit the worker service file
21. kubectl apply -f worker-service.yaml    # Apply the worker service
22. kubectl get deployments          # List deployments to check status
23. kubectl get services             # List services to check status
24. vi db-deployment.yaml            # Edit the database deployment file
25. kubectl apply -f db-deployment.yaml     # Apply the database deployment
26. vi db-service.yaml               # Edit the database service file
27. kubectl apply -f db-service.yaml        # Apply the database service
28. kubectl get deployments          # List deployments to check status
29. kubectl get services             # List services to check status
30. vi result-app-deployment.yaml    # Edit the result app deployment file
31. kubectl apply -f result-app-deployment.yaml  # Apply the result app deployment
32. vi result-app-service.yaml       # Edit the result app service file
33. kubectl apply -f result-app-service.yaml    # Apply the result app service
34. kubectl get deployments          # List deployments to check status
35. kubectl get services             # List services to check status
36. history                          # View command history


Voting App: http://18.221.95.100:30000
Result App: http://18.221.95.100:30001