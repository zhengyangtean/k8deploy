1. run "./adddashboard.sh"
2. run "kubectl proxy"
3. access the dashboard via "http://localhost:8001/api/v1/namespaces/kubernetes-dashboard/services/https:kubernetes-dashboard:/proxy/#!/login"
4. enter the token gotten from step 1 and login via token