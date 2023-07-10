# eureka-server-high-availability-example
 How to run with multiple replicas of microservice in different ports



java -jar -Dserver.port=8082 target/inventory-mgmt-service-1.0.jar
java -jar -Dserver.port=8083 target/inventory-mgmt-service-1.0.jar
java -jar -Dserver.port=8084 target/inventory-mgmt-service-1.0.jar


java -jar -Dserver.port=8085 target/automobile-production-service-1.0.jar
java -jar -Dserver.port=8086 target/automobile-production-service-1.0.jar
java -jar -Dserver.port=8087 target/automobile-production-service-1.0.jar

In eureka server the above 2 MS will have 3 replicas each

Localhost://8761