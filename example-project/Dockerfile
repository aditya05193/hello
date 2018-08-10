FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD example-project-1.0-SNAPSHOT.jar HelloWorld.jar
EXPOSE 8080
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /HelloWorld.jar" ]