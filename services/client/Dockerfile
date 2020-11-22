FROM node:12-alpine as build

WORKDIR /app

COPY package.json /app/package.json

RUN npm install --only=prod

COPY . .

EXPOSE 3000

CMD npm start