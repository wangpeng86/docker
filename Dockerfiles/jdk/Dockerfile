#Base image
FROM mcr.microsoft.com/java/jdk:8-zulu-ubuntu

#MAINTAINER
MAINTAINER wp

ADD web.jar /webdir/web.jar

RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime \
 && echo 'Asia/Shanghai' > /etc/timezone

CMD java -jar /webdir/web.jar
