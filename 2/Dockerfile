FROM butter/node:boron
LABEL maintainer="Butter.ai <dev@butter.ai>"

ENV \
  NGINX_VERSION=1.11.9-1~jessie

# Standard set up Nginx
RUN apt-key adv --keyserver hkp://pgp.mit.edu:80 --recv-keys 573BFD6B3D8FBC641079A6ABABF5BD827BD9BF62 \
 && echo "deb http://nginx.org/packages/mainline/debian/ jessie nginx" >> /etc/apt/sources.list \
 && apt-get update && apt-get install --no-install-recommends --no-install-suggests -y \
      ca-certificates \
      nginx=${NGINX_VERSION} \
      gettext-base \
 && rm -rf /var/lib/apt/lists/*

RUN groupadd -r butter && useradd -r -g butter butter

WORKDIR /usr/src/app/

COPY package.json /usr/src/app
RUN npm install
