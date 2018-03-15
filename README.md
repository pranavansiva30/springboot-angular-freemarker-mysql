Deployment :

go inside springboot-angular-freemarker-mysql 

     method:

     needed sofware(maven ,java 1.8,mysql)

    run the command mvn clean package
    go inside springboot-angular-freemarker-mysql /target
    
    for local Envoirment 
    
    java -jar springboot-angular-freemarker-mysql-1.0.0.jar --spring.profiles.active=local

    for prod Envoirment
    java -jar springboot-angular-freemarker-mysql-1.0.0.jar --spring.profiles.active=prod

    type localhost:8080/SpringBootCRUDApp in browser (localhost is host host name)



