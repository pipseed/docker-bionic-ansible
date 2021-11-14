# Docker file for my Home Lab
FROM ubuntu:20.04

LABEL maintainer="pipseed@gmail.com"
LABEL version="beta1"

RUN sed -i -r '/^deb/s/\w+\.ubuntu\.com/dev-kvm-03.ams1.info\/patching\/current\/mirror\/archive.ubuntu.com/' /etc/apt/sources.list

RUN apt update; apt upgrade -y; apt clean; rm -rf /var/lib/apt/lists/*