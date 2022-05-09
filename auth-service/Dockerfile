FROM node:latest

WORKDIR /app

copy . . 

RUN npm install

EXPOSE 7070

ENTRYPOINT ["node", "index.js"]
