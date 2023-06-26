## Quick Guide to Microservices with Spring Boot 2.0, Eureka and Spring Cloud  

$ oc login -u system:admin
$ oc policy add-role-to-user cluster-reader system:serviceaccount:myproject:default

$ kubectl create clusterrolebinding admin --clusterrole=cluster-admin --serviceaccount=default:default
