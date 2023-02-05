FROM node:13-alpine

WORKDIR /usr/src/app

COPY package*.json .

RUN npm install

COPY . .

# no need for /home/app/server.js because of WORKDIR
CMD ["npm", "start"]
