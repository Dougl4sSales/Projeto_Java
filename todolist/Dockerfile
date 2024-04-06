# Use the base image with Maven and OpenJDK 17
FROM maven:3.8.3-openjdk-17

# Add any additional configurations or dependencies you need here
# For example, you can copy your project code into the container

# Define a working directory (you can customize this)
WORKDIR /app

# Copy your project code into the container
COPY . /app

# Build your project
CMD ["tail", "-f", "/dev/null"]

# RUN mvn clean install

# You can customize this Dockerfile according to your project's requirements
