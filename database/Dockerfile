FROM mysql:8.0

ENV MYSQL_DATABASE your-databse-name
ENV MYSQL_ROOT_PASSWORD  your-password
ENV MYSQL_USER your-admin-user 
ENV MYSQL_PASSWORD your-admin-password 

COPY ./mysql.cnf /etc/mysql/conf.d/mysql.cnf
RUN chmod 644 /etc/mysql/conf.d/mysql.cnf 