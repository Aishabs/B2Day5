FROM node:10-alpine

ENV API_URL=${API_URL}

WORKDIR /var/www
COPY . .
RUN npm install

EXPOSE 3000

VOLUME [ "/var/www" ]
CMD [ "node", "index.js" ]
