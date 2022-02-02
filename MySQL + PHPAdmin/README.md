# Deploy: 

```
3 Statefull MySQL Databases: (ver: mysql:5.7)
 init-mysql
 Master
 Replica 
 Reader

```
```
# Resources & sidecars:

 # sidecar-mysql-monitoring (Instead use some java app i decide use a sidecar app 
 # that will fetch data every 30 seconds and you can acess via NodeIP)
 # xtrabackup
 # My PhpAdmin
 
 ```
 ```
 Run:
 
 kubectl create namespace mysql
 kubectl apply -f ./MySQL + PHPAdmin/
 kubectl get namespace
 
 
 - Wait all resources get status ready ( take few minutes)
 
 ```
 
 

 
