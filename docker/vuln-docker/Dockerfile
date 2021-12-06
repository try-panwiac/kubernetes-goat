FROM vulhub/node:8.5.0

MAINTAINER joe

ADD package.json package-lock.json /usr/src/

RUN set -ex \
    && cd /usr/src \
    && npm install

WORKDIR /usr/src

CMD ["npm", "run", "start"]

EXPOSE 22
