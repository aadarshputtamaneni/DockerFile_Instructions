FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD ADD index.html /usr/share/nginx/html/
CMD ["nginx","-g","daemon off;"]


## ONBUILD will instruct users to follow rules while building. while building this image onbuild will not run. If someone uses our image i will instruct the user to maintian index.html in there folder.