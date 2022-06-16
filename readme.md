## kind create cluster --name=esquenta
## kubectl cluster-info --context kind-esquenta
## kubectl get nodes

# cria o POD
## kubectl apply -f pod.yaml

# lista os pods
## kubectl get pods

# redireciona portas da localhost:pod
## kubectl port-forward pod/nginx 9090:80

# deleta um pod
## kubectl delete pod nginx

# cria um replicaset
## kubectl apply -f replicaset.yaml

# lista o replicaset criado
## kubectl get <replicaset>

# delete um pod do replicaset
## kubectl delete pod nginx-<fq94d>

# deleta um replicaset
## kubectl delete replicaset <nome>

# lista o deployment criado
## kubectl get <deployment>

# cria um service
## kubectl apply -f k8s/nginx/service.yaml