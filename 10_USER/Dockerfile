FROM almalinux:8
RUN adduser hari
USER hari
CMD ["sleep","1000"]


## We shouldn't run contianer with root access because all the containers are running on host if any user has root access he may access the underlying host storage.

## adduser command will execute with root acess after the USER instruction the next commands will execute will hari user.

## we are giving sleep 1000 sec to login to the container and check "id" it will show hari.

