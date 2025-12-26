FROM node:24-alpine

WORKDIR /what2eat_server

VOLUME [ "/what2eat_server/node_modules" ]

COPY package*.json ./
RUN npm install

CMD ["npm", "run", "start"]
