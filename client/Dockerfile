FROM node:12-alpine3.12 AS build
WORKDIR /home/Descargas/chat3
COPY package.json ./
RUN npm install
COPY . .
CMD ["npm","start"]
