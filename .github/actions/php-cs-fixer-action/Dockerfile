FROM oskarstark/php-cs-fixer-ga

RUN apt-get update && apt-get install -y libicu-dev g++
RUN docker-php-ext-configure intl
RUN docker-php-ext-install intl

COPY entrypoint.sh /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
