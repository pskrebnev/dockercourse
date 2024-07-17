FROM fedora:latest

RUN dnf install -y httpd

ADD website.tar.gz /var/www/html/

CMD [ "-D", "FOREGROUND" ]

ENTRYPOINT [ "/usr/sbin/httpd" ]

EXPOSE 80

