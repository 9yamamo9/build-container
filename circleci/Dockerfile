FROM hashicorp/terraform:0.14.9

RUN apk update --no-cache \
  && apk add --no-cache \
  wget \
  zip \
  unzip \
  curl \
  make \
  npm=14.16.1-r1 \
  yarn=1.22.10-r0 \
  aws-cli \
  jq
