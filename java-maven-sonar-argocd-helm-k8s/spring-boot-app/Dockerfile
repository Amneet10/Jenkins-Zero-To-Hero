# # Use a Maven image as the base image
# FROM maven:latest AS builder

# # Set the working directory in the image
# WORKDIR /usr/src/app

# # Copy the Maven project source code into the image
# COPY . .

# # Run the Maven build process
# RUN mvn clean package

# # Use a lightweight JRE image as the final base image
# FROM adoptopenjdk/openjdk11:alpine-jre

# # Set the working directory in the final image
# WORKDIR /opt/app

# # Copy the built JAR file from the builder stage to the final image
# COPY --from=builder /usr/src/app/target/*.jar app.jar

# # Define the command to run the application when the container starts
# ENTRYPOINT ["java","-jar","app.jar"]

