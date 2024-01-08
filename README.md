# Learning_k8s


ok so how I would structure it is

write a pod yaml for Moodle, postgres and redis . 
For now lite on redis. Let me do Moodle and Postgres

after that write the replicate yaml -> change to deplyment yaml

then clusterIP servive between the Moodle App and the postgres Backennd  (port , taegetport)

then External Serivice between app and outside - using LoadBalancer/NodePort -> for now node port -> (port, targetport,nodeport)



## Commands executed :

```bash
kind create cluster --name=cluster-k8s-ist --config=kind-config.yaml

```