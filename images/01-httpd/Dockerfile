FROM centos
RUN yum install httpd -y
RUN echo This is a sample httpd docker image html file >/var/www/html/index.html
CMD /usr/sbin/httpd -DFOREGROUND
