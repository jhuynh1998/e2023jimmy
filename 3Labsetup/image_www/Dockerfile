FROM handsonsecurity/seed-server:apache-php

ARG WWWDir=/var/www/SQL_Injection

COPY Code $WWWDir
COPY apache_sql_injection.conf  /etc/apache2/sites-available
EXPOSE 80
RUN  a2ensite apache_sql_injection.conf 



