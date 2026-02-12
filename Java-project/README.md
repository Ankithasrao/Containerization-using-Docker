# Containerization-of-Java-project-using-Docker 
### This project demonstrates how to create a simple Java application, build it using Maven, and containerize it using a multi-stage Dockerfile for optimal efficiency.

## Why containerization is important :

#### 1. Consumes low resources - We can save lot of money
#### 2. Best suitable for the micro-service architecture
#### 3. Same containers on different environment - Reusable and reputable

## Project Structure
```
java-app/
│── src/
│   └── main/
│       └── java/
│           └── com/example/Hello.java
│── pom.xml
│── Dockerfile
│── .gitignore
│── README.md

```
#### Ensure you have the following installed on your machine:

- java -version ## (8+ version)
- mvn -version
- git --version
- docker --version

### Docker - Build & Run
#### Below are the command to build the image using a multi-stage build Dockerfile and running an images for creating a container.

### Build Docker Image
```
docker build -t <NAME-OF-THE-IMAGE> .
```

```
docker run <NAME-OF-THE-IMAGE>
```
