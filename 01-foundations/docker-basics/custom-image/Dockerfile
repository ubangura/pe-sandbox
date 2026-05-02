FROM node:alpine3.22

WORKDIR /app

COPY package.json /app/
RUN npm install express

COPY src /app/

EXPOSE 3000
CMD ["node", "server.js"]