FROM redis:6.0

MAINTAINER wp

ADD redis.conf /etc/redis/

RUN cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime \
&&echo 'Asia/Shanghai' > /etc/timezone
