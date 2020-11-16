FROM alpine:3.12.1

RUN apk update --no-cache \
  && apk add --no-cache \
  ruby \
  ruby-bundler \
  ruby-dev \
  wget \
  zip \
  unzip \
  curl \
  make \
  terraform=0.12.25-r0 \
  npm=12.18.4-r0 \
  yarn=1.22.4-r0

RUN gem install miam