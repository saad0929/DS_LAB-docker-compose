FROM node:latest

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install
ENV PORT=3000
COPY . .

EXPOSE $PORT

CMD ["node","app.js"]