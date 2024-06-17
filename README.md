# filezilla-kubernetes-pipeline
Designated to deploy containerized FileFileZilla application to Kubernetes clusters.

# Environments
Staging pipeline deploys manifest in staging-general-colt-eksd Kubernetes cluster and added to staging branch.
Production pipeline deploys manifest in prod-general-colt-eksd Kubernetes cluster and added to production branch.

Use staging/production branch to update staging/production AZ pipeline respectively. 
Choose branch in [FileZilla Kubernetes Pipeline](https://infare.atlassian.net/wiki/spaces/DFS/pages/640516249/FTP+Synchronizer) on each run. 
