FROM trafex/php-nginx:latest

USER root
RUN apk add ldb-dev libldap openldap-dev 
RUN apk add php8-ldap php8-gettext php8-xmlwriter php8-gmp php8-zip
USER nobody
