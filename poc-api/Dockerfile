FROM node:14

WORKDIR /poc-api
COPY package.json .
RUN npm install
COPY . .
CMD npm start
