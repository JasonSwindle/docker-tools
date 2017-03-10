FROM alpine:latest

RUN apk add --no-cache python2 ca-certificates groff \
    && apk add --no-cache --virtual temp-pkgs \
        py2-pip \
    && pip2.7 install --no-cache-dir \
        awscli \
    && apk del --purge temp-pkgs

ENTRYPOINT ["aws"]
