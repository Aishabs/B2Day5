FROM node:10-alpine

ENV CONNECTION_STRING=${CONNECTION_STRING}

WORKDIR /var/www
COPY . .
RUN npm install

EXPOSE 3001

VOLUME [ "/var/www" ]
CMD [ "node", "index.js" ]