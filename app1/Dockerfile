FROM node:14

WORKDIR /usr/src/app1

COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 4000

CMD [ "node", "index.js" ]