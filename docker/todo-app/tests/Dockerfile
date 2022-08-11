FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app

EXPOSE 3001

ADD ./node_modules.tar.gz .
COPY . .

ENTRYPOINT [ "npm", "test" ]
