FROM ubuntu
RUN apt-get update \
 && apt-get install -y --no-install-recommends curl \
                                               openssl \
                                               ca-certificates \
 && rm -rf /var/lib/apt/lists/*
RUN curl --help
CMD ["/bin/sh"]

# sudo docker build -t curl-ubuntu --force-rm .