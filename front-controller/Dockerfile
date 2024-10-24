# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-slim

# Set the working directory
WORKDIR /app

# Copy your Spring Boot JAR file (assuming you have it locally)
COPY *.war app.war

# Expose the port your application runs on
EXPOSE 8080

# Run the Spring Boot application
CMD ["java", "-jar", "app.war"]
