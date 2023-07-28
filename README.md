# ansible-semaphore-deployment

### Заготовки

https://docs.ansible-semaphore.com/  
https://github.com/ansible-semaphore/semaphore  
  
```  
kubectl create ns semaphore  
```  
```  
kubectl -n semaphore apply -f manifests  
```  
```  
kubectl -n semaphore delete -f manifests  
```  
  
#### База данных.  
  
```
kubectl -n semaphore apply -f postgres/postgreesql.yaml  
```  
  
```  
kubectl -n semaphore delete -f postgres/postgreesql.yaml  
```
