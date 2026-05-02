FROM node:alpine3.22

WORKDIR /app

COPY package.json /app/
COPY src /app/

RUN npm install express

EXPOSE 3000
CMD ["node", "server.js"]