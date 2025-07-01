FROM almalinux:9
RUN yum install nginx -y
CMD ["nginx","-g","daemon off;"]


## Almalinux is same a centos.
## RUN is executed at the time of build an image. While building the image we have to install nginx.
## CMD is executed at container run time. If nginx is running then only we can say container is running here systemctl won't work in a container so we are giving ["nginx","-g","daemon off;"] command to CMD to keep the service running.

## The main purpose of the CMD command is to launch the software required in a container.

##Multiple CMD will be allowed in a dockerfile but it will execute only the last one.


## Command to build image from this dockerfile for local use:
## docker build -t <image_name>:<version> .

## TO test the CMD we have to run the container.
## docker run -d -p <host_port>:<container_port> <image_name>:<version>