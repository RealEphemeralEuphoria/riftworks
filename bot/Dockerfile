FROM busybox:1.38

RUN mkdir -p /www && echo ok > /www/healthz

USER 65534:65534

EXPOSE 8080

CMD ["httpd", "-f", "-p", "8080", "-h", "/www"]
