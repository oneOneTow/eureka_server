FROM java:8
VOLUME /temp/
ADD eureka_server-1.0-SNAPSHOT.jar /docker_data/eureka_server.jar
EXPOSE 8761
ENTRYPOINT ["java","-jar","/docker_data/eureka_server.jar"]