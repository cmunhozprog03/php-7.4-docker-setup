FROM phpdockerio/php:7.4-fpm
WORKDIR "/app"

RUN apt-get update; \
    apt-get -y --no-install-recommends install \
        git \ 
        php7.4-bcmath \ 
        php7.4-imagick \ 
        php7.4-memcached \ 
        php7.4-mysql \ 
        php7.4-redis; \
    apt-get clean; \
    rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*
