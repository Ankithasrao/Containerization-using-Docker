## Containerization-of-Nodejs-project-using-Docker 
### This application is a simple HTTP server built using Node.js.

### Project Structure
```
node-docker-app/
│
├── Dockerfile
├── package.json
├── server.js
└── README.md
```
### Tech Stack
- Node.js (v20)
- Docker
- Git & GitHub
- Linux (Ubuntu / EC2 environment)

#### File Description
- server.js → Simple Node HTTP server
- package.json → Project metadata & start script
- Dockerfile → Container configuration
- README.md → Project documentation

#### Below are the command to build the image using a multi-stage build Dockerfile and running an images for creating a container.

### Build Docker Image
```
docker build -t <NAME-OF-THE-IMAGE> .
```

```
docker run <NAME-OF-THE-IMAGE>
```
