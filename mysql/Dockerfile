FROM mysql:5.7
#we setup root p.w,shiping user & created database automaticaly.& shipping data loading into cities
ENV MYSQL_ROOT_PASSWORD_=RoboShop@1 \
    MYSQL_DATABASE=cities \
    MYSQL_USER=shipping \
    MYSQL_PASSWORD=RoboShop@1
COPY scripts/* /docker-entypoint-initdb.d/