FROM almalinux:8
ARG username
RUN adduser $username
USER $username
CMD ["sleep","100"]


## ARG instruction will pass the arguments while building the image. We are not hard coding and pass the values in command.
## ENV can pass the arguments while building image and running container.

##To pass the user name during building an image
## docker build -t <image_name>:<version> --build-arg <key>=<value> .
## docker build -t arg:v1 --build-arg username=hari

##Run command will take the username from ARG and to ARG instruction we are passing via commnad during build.