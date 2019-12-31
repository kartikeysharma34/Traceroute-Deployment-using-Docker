# Traceroute-Deployment-using-Docker

Traceroute computer network diagnostic commands for displaying the route (path) and measuring transit delays of packets across an Internet Protocol (IP) network. The history of the route is recorded as the round-trip times of the packets received from each successive host (remote node) in the route (path); the sum of the mean times in each hop is a measure of the total time spent to establish the connection. Traceroute proceeds unless all (three) sent packets are lost more than twice; then the connection is lost and the route cannot be evaluated.

# Docker

Docker image was created on an Ubuntu machine from scrath which was later deployed on required end-user devices as a container.

# Docker Build 

- sudo docker build *path* -t *username/app-name*

# Docker Run

- sudo docker run *username/app-name*

# Uploading the image on Docker Hub

- sudo docker push *username/app-name*


For more information on Docker: https://docs.docker.com/
