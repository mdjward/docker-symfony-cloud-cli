FROM php:7.3-cli-alpine3.8

RUN apk add --no-cache curl git

RUN apk add --no-cache bash && \
    curl -sS https://get.symfony.com/cli/installer | bash && \
    ln -s ~/.symfony/bin/symfony /usr/local/bin/symfony && \
    apk del bash
