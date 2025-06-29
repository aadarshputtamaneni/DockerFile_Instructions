FROM almalinux:8
WORKDIR /tmp
RUN echo "Hello Docker" > hello.txt
CMD ["sleep", "100"]


## cd /tmp will not work here we have to use WORKDIR 
## Commands that we give after WORKDIR will run in /tmp folder even we login to the service we will launch to /tmp directly