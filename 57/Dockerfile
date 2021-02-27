FROM mysql:5.7
LABEL maintainer="edson@xsinformatica.com.br"

COPY mysqllog.sh /usr/local/bin/
RUN chmod +x /usr/local/bin/mysqllog.sh 
RUN /usr/local/bin/mysqllog.sh