FROM node:14.4-alpine3.11

WORKDIR /frontend

EXPOSE 3000

ADD node_modules.tar.gz .

COPY . .

RUN npm install