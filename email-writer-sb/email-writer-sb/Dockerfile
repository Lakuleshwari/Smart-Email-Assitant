
FROM openjdk:17-jdk-slim


WORKDIR /app


COPY target/email-writer-sb-0.0.1-SNAPSHOT.jar email-writer-sb.jar

EXPOSE 8080

CMD ["java", "-jar", "email-writer-sb.jar"]
