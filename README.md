# Deploy opentsdb on Kubernetes cluster

kubectl apply -f opentsdb-pv.yaml \
kubectl apply -f opentsdb-claim0-persistentvolumeclaim.yaml \
kubectl apply -f opentsdb-deployment.yaml \
kubectl apply -f opentsdb-service.yaml \
