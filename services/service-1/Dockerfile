# Use a base image
FROM openjdk:11-jre-slim

# Set the working directory
WORKDIR /app

# Copy the jar file
COPY build/libs/service-1.jar /app/service-1.jar

# Run the application
ENTRYPOINT ["java", "-jar", "service-1.jar"]
