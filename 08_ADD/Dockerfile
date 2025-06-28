FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
EXPOSE 80/tcp
COPY index.html /usr/share/nginx/html/
ADD  https://github.com/aadarshputtamaneni/Expense-Infra-Development.git /tmp/
ADD sample-1.tar /tmp/ 
CMD ["nginx","-g","daemon off;"]

## COPY & AND is used to copy the files and directories from local to image.
## The index.html should be where the dockerfile is 

##AND is having extra capabilities than COPY
## AND can download the file from internet/remote.[Copied something from my github to /tmp]
## AND can untar the files.[sample-1.tar file is in my local 08_Dockerfile from here copying it into the /tmp ]