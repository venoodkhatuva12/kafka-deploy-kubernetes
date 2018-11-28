# kafka-deploy-kubernetes
Kafka for Kubernetes with Zookeeper
This community seeks to provide:

Production-worthy Kafka setup for persistent (domain- and ops-) data at small scale.
Operational knowledge, biased towards resilience over throughput, as Kubernetes manifest.
A platform for event-driven (streaming!) microservices design using Kubernetes.
To quote @venood12:

thanks for creating and maintaining this Kubernetes files, they're up-to-date (unlike the kubernetes contrib files, don't require helm and work great!

Getting started
We suggest you to download or clone the repo.
 git clone https://github.com/venoodkhatuva12/kafka-deploy-kubernetes.git

kubectl apply -f /kafka-deploy-kubernetes

That'll give you client "bootstrap" kafka.namespace.svc.cluster.local:9092.
