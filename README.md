# Kubernetes Redis Deployment
A starter base for deploying Redis in a Kubernetes cluster. 

This deployment configuration is intended for use within a development environment.

A default password of "password" is provided to make deployment & development simple.



### Deployment Process
---
1. ```cd ./scripts```

2. ```kubectl apply -f config.yaml```

3. ```kubectl apply -f volume.yaml```

4. ```kubectl apply -f redis.yaml```

### Identifying the port the service is exposed on
---
1. ```kubectl get services --all-namespaces```