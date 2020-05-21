# Deploy opentsdb on Kubernetes cluster

kubectl apply -f opentsdb-pv.yaml,\
opentsdb-claim0-persistentvolumeclaim.yaml,\
opentsdb-deployment.yaml,\
opentsdb-service.yaml
