FROM node:20-alpine

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

# Railway définit automatiquement le port via PORT env var
# On n'a pas besoin d'EXPOSE car Railway gère cela automatiquement

CMD ["node", "server.js"]