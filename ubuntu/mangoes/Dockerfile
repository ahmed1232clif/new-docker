FROM ubuntu

RUN apt update -y 
RUN apt install apache2 -y

RUN rm /var/www/html/index.html

RUN apt-get install systemctl -y

RUN systemctl start apache2

COPY index.html /var/www/html/ 

EXPOSE 80