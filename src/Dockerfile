FROM node:17.1.0-stretch

WORKDIR /app

COPY /package*.json ./

RUN npm install

COPY ./ ./

EXPOSE 8181

CMD [ "node", "server.js" ]