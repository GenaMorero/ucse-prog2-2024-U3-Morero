FROM node:14

WORKDIR /usr/src/app2

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 4001

CMD [ "node", "index.js" ]