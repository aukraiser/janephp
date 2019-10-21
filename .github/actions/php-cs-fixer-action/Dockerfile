FROM oskarstark/php-cs-fixer-ga

RUN docker-php-ext-configure intl
RUN docker-php-ext-install intl

COPY entrypoint.sh /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
