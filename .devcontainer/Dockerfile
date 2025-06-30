FROM codercom/enterprise-desktop:latest

USER root

ENV SHELL=/bin/bash

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends libdatetime-perl

ARG USER=coder
USER coder