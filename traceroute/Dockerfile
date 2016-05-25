FROM alpine:3.3
MAINTAINER github.com/JasonSwindle/docker-tools
LABEL Architecture="x86_64" Description="Traceroute Dockerized and placed into the ENTRYPOINT." Usage="docker run jasonswindle/docker-tools:traceroute google.com"
RUN apk add --no-cache iputils
ENTRYPOINT ["traceroute"]
