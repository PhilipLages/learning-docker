FROM node:14

WORKDIR /app

EXPOSE 3000

ADD node_modules.tar.gz .

COPY package*.json ./
COPY ./src ./src
COPY ./public ./public


CMD [ "npm", "start" ]
