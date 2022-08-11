FROM node:10-alpine

WORKDIR /var/www
COPY . .
RUN npm install

EXPOSE 3001

VOLUME [ "/var/www" ]
CMD [ "node", "index.js" ]