# Hello-World
# Simple Python Flask Dockerized Application
Build the image using the following command

$ docker build -t simple-flask-app:latest .
Run the Docker container using the command shown below.

$ docker run -d -p 8000:8000 simple-flask-app
The application will be accessible at http:127.0.0.1:8000 or if you are using boot2docker then first find ip address using $ boot2docker ip and the use the ip http://<host_ip>:8000
