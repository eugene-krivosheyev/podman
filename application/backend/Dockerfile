FROM openjdk:11-jre-slim
EXPOSE 8080
WORKDIR /dbo
COPY dbo-1.0-SNAPSHOT.jar ./app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]
CMD ["--spring.profiles.active=qa"]
