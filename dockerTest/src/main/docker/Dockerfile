FROM openjdk:latest
VOLUME /tmp
ADD dockerTest-1.0-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
# 映射多个端口
EXPOSE 8080