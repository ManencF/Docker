FROM scratch
MAINTAINER Robin FREDON

ADD rootfs.tar.xz /

RUN apt-get update && apt-get install -y apache2 ansible

ADD ./apache-conf/* /etc/apache2/

ENTRYPOINT ["/usr/sbin/apache2ctl","-D","FOREGROUND"]

