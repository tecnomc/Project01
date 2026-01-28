FROM adoptopenjdk/openjdk11:alpine-jre

WORKDIR /opt/app

# Copy the artifact into the container
COPY spring-boot-web.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "app.jar"]
