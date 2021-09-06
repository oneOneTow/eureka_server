docker build -t eureka-server:3.0 .
docker run -d --name eureka-server eureka-server:3.0 -p 8081:8081 --错误示范
docker run --name eureka-server -p 8081:8081 -d eureka-server:3.0