FROM mysql:5.6

RUN apt-get update

EXPOSE 3306
ADD init.sql /docker-entrypoint-initdb.d


sudo ln -s /usr/local/lib/node_modules/cnpm/bin/cnpm /usr/local/bin/cnpm

