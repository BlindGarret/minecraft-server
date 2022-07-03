helm repo add itzg https://itzg.github.io/minecraft-server-charts/

helm install minecraft -f values.yaml itzg/minecraft -n minecraft --create-namespace 
