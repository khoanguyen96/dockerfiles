FROM mhart/alpine-node:latest

RUN wget -q -O /etc/apk/keys/sgerrand.rsa.pub https://alpine-pkgs.sgerrand.com/sgerrand.rsa.pub \
  && wget https://github.com/sgerrand/alpine-pkg-glibc/releases/download/2.28-r0/glibc-2.28-r0.apk \
  && apk --no-cache add glibc-2.28-r0.apk

RUN apk --no-cache add \
  build-base \
  chromium \
  git \
  python \
  ttf-freefont \
  udev
