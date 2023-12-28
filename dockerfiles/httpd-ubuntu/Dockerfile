FROM ubuntu:20.04
RUN apt-get update -y && \
    apt-get install apache2 -y  && \
    apt-get install -y apache2-utils && \
    apt-get install -y curl && \
    apt-get install -y vim 
RUN apt-get clean
RUN echo "Hello Ather" > /var/www/html/index.html
RUN mkdir /apache/data/ 
EXPOSE 80 
CMD ["apache2ctl", "-D", "FOREGROUND"] 
    