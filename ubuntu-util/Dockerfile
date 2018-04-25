#
# Ubuntu image with useful utilities
#

FROM ubuntu:latest
LABEL maintainer = "Anders Zommarin <anderd@zommarin.se>"

RUN apt update && \
    apt install -y \
    net-tools iputils-ping iproute2 ethtool dnsutils \
    htop \
    emacs-nox \
    less

COPY entrypoint.sh /use/bin/entrypoint.sh

ENTRYPOINT ["entrypoint.sh"]
