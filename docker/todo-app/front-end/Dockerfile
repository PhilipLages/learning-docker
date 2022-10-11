FROM node:14

WORKDIR /app/frontend/

EXPOSE 3000

COPY . .

RUN npm install

ADD node_modules.tar.gz .

ENTRYPOINT [ "npm", "start" ]
