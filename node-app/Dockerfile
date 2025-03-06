FROM node:16-alpine

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

RUN npm install

#TO Start the application
CMD [ "npm","run","dev" ]