FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app

COPY ./e2e/ ./e2e/
COPY jest.config.js .
COPY package*.json .

ADD node_modules.tar.gz .

ENTRYPOINT [ "npm", "test" ]
