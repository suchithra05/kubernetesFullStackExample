FROM openjdk:8-jdk-alpine
ENTRYPOINT ["/usr/bin/java", "-jar", "/usr/share/myservice/student-app-api-0.0.1-SNAPSHOT.jar"]
ADD target/student-app-api-0.0.1-SNAPSHOT.jar  /usr/share/myservice/lib
ARG JAR_FILE=student-app-api-0.0.1-SNAPSHOT.jar
ADD target/${JAR_FILE} /usr/share/myservice/student-app-api-0.0.1-SNAPSHOT.jar
EXPOSE 8080
