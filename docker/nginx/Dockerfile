FROM nginx:1.11

RUN usermod -u 1000 www-data && groupmod -g 1000 www-data

RUN apt-get update && apt-get install -y \
    vim \
    unzip \
    zip \
    git 

WORKDIR /var/www/html