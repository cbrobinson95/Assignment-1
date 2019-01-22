# Need to use mysql v5.7 for wordpress

FROM mysql:5.7

# Set the root password, the wordpress container will pick it up from here

ENV MYSQL_ROOT_PASSWORD=csci459

COPY createuser.mysql .
COPY createdata.mysql .

