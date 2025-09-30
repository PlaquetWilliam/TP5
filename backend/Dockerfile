FROM node:20-alpine

WORKDIR /app

RUN npm install

COPY . .

EXPOSE 8000

CMD ["node", "server.js"]