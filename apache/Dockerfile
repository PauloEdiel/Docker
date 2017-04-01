FROM ubuntu:14.04
RUN apt-get update && apt-get install -y apache2 && apt-get clean
RUN /etc/init.d/apache2 start 
EXPOSE 80
CMD /bin/bash
