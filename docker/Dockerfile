FROM "centos"

 RUN yum install -y java
 ADD spring-boot-web-0.0.1-SNAPSHOT.jar /app/spring-boot-web-0.0.1-SNAPSHOT.jar
 WORKDIR /app
 EXPOSE 8080

 ENTRYPOINT [ "java", "-jar", "spring-boot-web-0.0.1-SNAPSHOT.jar"]