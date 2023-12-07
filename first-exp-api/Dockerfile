FROM node:21-alpine3.18
WORKDIR /app
ADD package*.json .
RUN npm install
ADD . .
RUN npm install
CMD node index.js