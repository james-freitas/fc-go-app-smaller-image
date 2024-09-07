# Sample Golang application
Simple golang application optimized image

## ✔️ Requirements
- Docker

## 🍔 Stack
- Golang

## ✈️ How to run locally

1. Go to the root folder of this project 
`cd golang`

2. Build the image
`docker build -t <your_docker_user>/<image_name>:latest . -f Dockerfile.prod`

3. Run the application using
`docker run -it --rm --name goapp <your_docker_user>/<image_name>`

4. Check the size of the image with the command
`docker images | grep <your_docker_user>/<image_name>`