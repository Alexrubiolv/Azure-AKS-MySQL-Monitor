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

 # sidecar-mysql-monitoring (will fetch data every 30 seconds and you can acess via NodeIP)
 # xtrabackup
 # My PhpAdmin
 
 ```
 ```
 Run:
 
 kubectl apply -f ./MySQL + PHPAdmin/
 
 - Wait all resources get status ready ( take few minutes)
 
 ```
 
 

 
