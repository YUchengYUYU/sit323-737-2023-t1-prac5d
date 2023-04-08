FROM node:16

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY week4.js .

EXPOSE 4010
CMD ["node", "week4.js" ]