FROM node:10-alpine

WORKDIR /var/www
COPY . .
RUN npm install

EXPOSE 3000

VOLUME [ "/var/www" ]
CMD [ "node", "index.js" ]