FROM java:8
VOLUME /tmp
ADD target/spring-boot.jar spring-boot.jar
EXPOSE 8080
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
RUN sh -c 'touch /app.jar'
