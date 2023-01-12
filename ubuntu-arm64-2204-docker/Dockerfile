FROM arm64v8/ubuntu:22.04

ENV DEBIAN_FRONTEND=noninteractive
ADD qemu-aarch64-static /usr/bin

RUN apt update \
    && apt install docker-io
