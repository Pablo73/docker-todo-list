FROM mjgargani/puppeteer:trybe1.0
WORKDIR /tests

ADD ./node_modules.tar.gz .

EXPOSE 3000

COPY ./ .

ENTRYPOINT ["npm", "test"]
