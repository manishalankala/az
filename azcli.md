
# AKS

| Command | Description |
| ------------- | ------------- |
| az login | Login |
| az aks get-versions --location $REGION -o table | Get k8s available versions |
| az aks get-credentials --resource-group $RESOURCE_GROUP --name $CLUSTER_NAME | To configure kubectl to connect to your Kubernetes cluster |
| az aks browse --resource-group $RESOURCE_GROUP --name $CLUSTER_NAME | Open k8s Dashboard |
| az aks show  --resource-group $RESOURCE_GROUP --name $CLUSTER_NAME -o table | Get AKS Cluster info |
| az aks show --resource-group $RESOURCE_GROUP --name $CLUSTER_NAME --query nodeResourceGroup -o tsv | Get Node Resource Group |
| az aks scale --name $CLUSTER_NAME --resource-group $RESOURCE_GROUP --node-count $NODE_COUNT | Scale AKS Cluster nodes |
| git status |  |
| git status |  |
| git status |  |
| git status |  |
| git status |  |




# ACR


| Command | Description |
| ------------- | ------------- |
| az acr create --resource-group $RESOURCE_GROUP --name $ACR_NAME --sku Basic|  |
| az acr list -o table |  |
| az acr show -n $ACR_NAME -g $RESOURCE_GROUP |  |
| az acr show -n $ACR_NAME -g $RESOURCE_GROUP --query "id" -o tsv |  |
| az acr repository list -n $ACR_NAME -o table |  |
| az acr repository show  -n $ACR_NAME --repository $REPO_NAME -o table |  |
| az acr login --name $ACR_NAME |  |


   





