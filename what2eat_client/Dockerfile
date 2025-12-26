FROM node:24-alpine

WORKDIR /what2eat_client

VOLUME [ "/what2eat_client/node_modules" ]

COPY package*.json ./
RUN npm install

CMD ["npm" "run" "build-start"]
