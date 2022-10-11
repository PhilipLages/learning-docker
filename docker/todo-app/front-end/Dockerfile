FROM node:14

WORKDIR /app

EXPOSE 3000

COPY package*.json .
COPY ./src/ ./src/
COPY ./public/ ./public/

ADD node_modules.tar.gz .

ENTRYPOINT [ "npm", "start" ]
