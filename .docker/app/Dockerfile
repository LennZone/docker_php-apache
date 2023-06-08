FROM php:8.1-apache

RUN echo " \
    export LS_OPTIONS='--color=auto' \n \
    alias ls='ls \$LS_OPTIONS' \n \
    alias ll='ls \$LS_OPTIONS -la' \n \
    alias l='ls \$LS_OPTIONS -lA' \n \
    alias rm='rm -i' \n \
    alias cp='cp -i' \n \
    alias mv='mv -i' \n " >> /etc/bash.bashrc