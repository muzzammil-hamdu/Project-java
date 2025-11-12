FROM openjdk:8
WORKDIR /app
COPY target/frontend-1.0-RELEASE.jar /app/frontend.jar
EXPOSE 8085
CMD ["java", "-jar", "frontend.jar"]
