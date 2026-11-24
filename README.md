# Simple demo  Java Docker Project For practice 

## Overview
This project demonstrates how to containerize a Java application using Docker.

## Technologies Used
- Java 17
- Docker
- Dockerfile

## How It Works
1. The Dockerfile defines the Java base image and working directory.
2. The Java source code is copied into the image.
3. `javac` compiles the Java application.
4. The Docker container runs the compiled Java program and prints a greeting with the current date and time.

## Build the Docker Image
```bash
docker build -t java-app .
```

## Run the Application
```bash
docker run --rm java-app
```

## Expected Output
```text
Hello, Docker! Current date: [current date and time]
```

## Learning Objectives
- Understanding Docker images and containers
- Writing a Dockerfile
- Compiling and running Java inside Docker
- Using Git and GitHub for version control
