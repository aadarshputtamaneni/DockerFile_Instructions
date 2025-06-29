FROM almalinux:8
#CMD ["ping", "google.com"] 
#ENTRYPOINT ["ping", "google.com"] 
CMD ["google.com"]
ENTRYPOINT ["ping"]


## CMD can be overwridden during run time. 
## Ex: docker run -it <image_name>:<version> ping yahoo.com
## ENTRYPOINT command can't be overridden, if you try to do so, the command you are entering at run time will go and append to ENTRYPOINT

## We can use CMD and ENTRYPOINT for best results

## 1. You can use CMD instruction to supply default arguements to ENTRYPOINT
## 2. user can always override CMD arguements from run time