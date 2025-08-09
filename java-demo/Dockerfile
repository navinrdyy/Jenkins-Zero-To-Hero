# Use a base image with Java Development Kit (JDK) pre-installed
FROM openjdk:17-jdk-sli

# Set the working directory inside the container
#WORKDIR /home/naveeman/.jenkins/workspace/java_demo
WORKDIR /home/naveeman

# Copy the Java source file into the container
COPY src/HelloWorld.java .

# Compile the Java source file
RUN javac HelloWorld.java

# Define the command to run when the container starts
CMD ["java", "HelloWorld"]
