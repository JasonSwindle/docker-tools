FROM alpine:3.3
MAINTAINER github.com/JasonSwindle/docker-tools
LABEL Architecture="x86_64" Description="Curl Dockerized and placed into the ENTRYPOINT." Usage="docker run jasonswindle/docker-tools:curl google.com"
RUN apk add --no-cache curl
ENTRYPOINT ["curl"]
