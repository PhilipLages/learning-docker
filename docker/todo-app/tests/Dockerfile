FROM mjgargani/puppeteer:trybe1.0

WORKDIR /app/tests

COPY . .

RUN npm install

ADD node_modules.tar.gz .

ENTRYPOINT [ "npm", "test" ]
