FROM alpine:3.12.1

ENV terraform_version=0.13.5

RUN pwd

RUN apk update --no-cache \
  && apk add --no-cache \
  ruby \
  ruby-bundler \
  ruby-dev \
  wget \
  unzip \
  curl \
  terraform=0.12.25-r0

RUN gem install miam