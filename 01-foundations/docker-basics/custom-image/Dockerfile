FROM node:alpine3.22

WORKDIR /app

COPY package.json /app/
COPY src /app/

RUN npm install express

CMD ["node", "server.js"]