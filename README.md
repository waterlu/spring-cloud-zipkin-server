# spring-cloud-zipkin-server

mvn clean package -Dmaven.test.skip docker:build
docker run --name zipkin-server -d -p 10010:10010 spring-cloud/zipkin-server
docker logs -f config-server