FROM nextcloud:22

RUN apt-get update && apt-get install -y smbclient libsmbclient-dev libmagickcore-6.q16-6-extra && pecl install smbclient && docker-php-ext-enable smbclient