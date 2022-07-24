#To run ArgoCD as pod

1. follow this steps https://argo-cd.readthedocs.io/en/stable/getting_started/
2. Once you chanege the service type as LoadBalancer, AWS will automatically create a load balancer and you can  go to the load balancer section and get the access URL to access the service from anywhere.
3. You dont need to configure Ingress in aws EKS.
4. If you don't want to expose the service outside, then you can simply port-forward and use the localhost ip to access the service.
5. To get the login secret, Run the command mentioned in the above link in Gitbash CLI

#Create Application in ArgoCD:
1. Follow this link: https://www.youtube.com/watch?v=o4QG_kqYvHk&list=WL&index=3&t=1535s
