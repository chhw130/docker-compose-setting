FROM node

WORKDIR /app

COPY package.json ./

RUN npm install

COPY . ./
# COPY. /app

EXPOSE 80

CMD ["node", "server.js"]