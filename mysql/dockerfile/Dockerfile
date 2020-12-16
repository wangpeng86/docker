FROM mysql:5.7

MAINTAINER wp

ADD mysqld.cnf /etc/mysql/mysql.conf.d/

RUN cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime \
&&echo 'Asia/Shanghai' > /etc/timezone
