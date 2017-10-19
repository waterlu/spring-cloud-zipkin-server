# spring-cloud-zipkin-server

* mvn clean package -Dmaven.test.skip docker:build
* docker run --name zipkin-server -d -p 9411:9411 spring-cloud/zipkin-server
* docker logs -f zipkin-server