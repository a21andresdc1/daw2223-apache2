FROM debian
RUN apt-get update && apt-get install -y apache2 php libapache2-mod-php

RUN a2enmod ssl

EXPOSE 80
EXPOSE 443

WORKDIR /app

CMD apachectl -D FOREGROUND
