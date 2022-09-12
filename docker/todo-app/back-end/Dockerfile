FROM node:14.4-alpine3.11

WORKDIR /backend

EXPOSE 3001

ADD node_modules.tar.gz .

COPY . .

RUN npm install