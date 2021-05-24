FROM hashicorp/terraform:0.14.9

RUN apk update --no-cache \
  && apk add --no-cache \
  alpine-sdk \
  build-base \
  wget \
  zip \
  unzip \
  curl \
  make \
  npm=14.16.1-r1 \
  yarn=1.22.10-r0 \
  aws-cli \
  jq \
  libc6-compat \
  gcc \
  docker \
  docker-cli \
  openrc

RUN rc-update add docker boot

ENV GO_VERSION=1.16.4
RUN wget https://golang.org/dl/go${GO_VERSION}.linux-amd64.tar.gz
RUN tar -C /usr/local -xzf go${GO_VERSION}.linux-amd64.tar.gz
ENV PATH $PATH:/usr/local/go/bin
RUN go version
