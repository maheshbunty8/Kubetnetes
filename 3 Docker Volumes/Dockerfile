FROM node:20-alpine

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 8000

#VOLUME [ "namedVolumne:/app/feedback" ]

CMD [ "node", "server.js" ]