FROM php:fpm-alpine
# Utilise une petite image

RUN apk update; \
    apk upgrade;
# Mets à jour le seveur

# Install mysqli
RUN docker-php-ext-install mysqli

