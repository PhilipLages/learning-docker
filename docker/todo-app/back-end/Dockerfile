FROM node:14

WORKDIR /app

EXPOSE 3001

COPY package*.json .
COPY ./src/ ./src/

ADD node_modules.tar.gz  .

ENTRYPOINT [ "npm", "start" ]
