#Base image
FROM nginx:1.19

#MAINTAINER
MAINTAINER wp

ADD default.conf /etc/nginx/conf.d/
ADD web.tar.gz /data/webdir/

RUN cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime \
 && echo 'Asia/Shanghai' > /etc/timezone
