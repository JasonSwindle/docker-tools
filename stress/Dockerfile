FROM alpine:3.4
MAINTAINER github.com/JasonSwindle/docker-tools
LABEL Architecture="x86_64" Description="Stress Dockerized and placed into the ENTRYPOINT." Usage="docker run jasonswindle/docker-tools:stress --cpu 2 --io 1 --vm 2 --vm-bytes 128M --timeout 10s"
RUN apk add --no-cache stress
ENTRYPOINT ["stress"]
CMD ["--help"]
