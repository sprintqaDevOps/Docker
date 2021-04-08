FROM centos
# ENV var1 1234
RUN yum -y install httpd 
RUN echo "This is going to be my website" > /var/www/html/index.html
# COPY html-code /var/www/html
CMD apachectl -DFOREGROUND