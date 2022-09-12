FROM node:14

WORKDIR /frontend/

EXPOSE 3000

ADD node_modules.tar.gz .

COPY . .

ENTRYPOINT [ "npm" , "start"]