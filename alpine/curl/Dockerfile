FROM alpine
RUN apk update \
 && apk add --no-cache curl \
                       openssl \
                       ca-certificates \
 && rm -rf /var/cache/apk/*
RUN curl --help
CMD ["/bin/sh"]

# sudo docker build -t curl-alpine --force-rm .