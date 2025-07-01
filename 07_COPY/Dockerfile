FROM almalinux:9
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
EXPOSE 80/tcp
COPY index.html /usr/share/nginx/html/
CMD ["nginx","-g","daemon off;"]

## COPY is used to copy the files and directories from local to image.
## The index.html should be where the dockerfile is 