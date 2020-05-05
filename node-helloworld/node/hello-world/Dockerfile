From node:13-alpine3.10

EXPOSE 3000

USER root

RUN mkdir -p /usr/node/helloworld

RUN chmod 777 -R /usr/node/helloworld

WORKDIR /usr/node/helloworld

RUN npm install

RUN npm install express --save

COPY . .

CMD [ "node", "app.js" ]

