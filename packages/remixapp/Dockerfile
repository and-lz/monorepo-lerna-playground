FROM node:16.14.2-alpine 

WORKDIR /app

ADD package.json .
RUN npm install
RUN npm run build