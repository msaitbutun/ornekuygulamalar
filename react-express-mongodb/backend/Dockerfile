# syntax=docker/dockerfile:1.4

FROM node:lts-buster-slim

# Create app directory
WORKDIR /usr/src/app

# Install nodemon globally
RUN npm install -g nodemon

COPY package.json /usr/src/app/package.json
COPY package-lock.json /usr/src/app/package-lock.json
RUN npm ci

COPY . /usr/src/app

EXPOSE 3000

CMD [ "nodemon", "server.js" ]  # npm run dev yerine nodemon doğrudan çalıştırılacak
