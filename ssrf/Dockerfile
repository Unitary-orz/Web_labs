FROM php:5.6-apache

MAINTAINER youyouorz

RUN apt-get update && \
    apt-get install -y git && \
    apt-get clean

RUN git clone https://github.com/incredibleindishell/SSRF_Vulnerable_Lab.git && \
    mv SSRF_Vulnerable_Lab/* /var/www/html/
