# Use a base OpenJDK image
FROM openjdk:8

# Set working directory
WORKDIR /app

# Copy the built JAR from Maven target directory
COPY target/frontend-1.0-RELEASE.jar /app/frontend.jar

# Expose frontend port
EXPOSE 8085

# Run the JAR
CMD ["java", "-jar", "frontend.jar"]
