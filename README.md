# Spring Microservices Demo

## Useful links

- eureka http://localhost:8761/
- api gateway (built-in load balancer) http://localhost:8765
- http://localhost:8765/eclient/main/test <=> http://localhost:8765/main/test
- http://localhost:8765/eclient2/new/name <=> http://localhost:8765/new/name
- настройки eureka-client http://localhost:8888/eureka-client/default

## Для **config server**

- application.properties - считают все
- application-micro.properties - считают, кому нужен профайл micro
- api-gateway.properties - конкретный сервис
- eureka-server.properties - конкретный сервис

## Актуатор
![Актуатор](./images/actuator.png)
