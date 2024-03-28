FROM openjdk:17-alpine
COPY ./target/spring_app.jar .
EXPOSE 8080
ENTRYPOINT [ "java", "-jar", "spring_app.jar" ]
