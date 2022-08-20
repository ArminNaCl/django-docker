FROM node:16

WORKDIR /opt/frontend

COPY package.json  ./opt/frontend
COPY yarn.lock  ./opt/frontend

RUN yarn

COPY . /opt/frontend/

