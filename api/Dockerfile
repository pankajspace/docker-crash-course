FROM node:17-alpine

COPY package.json .

WORKDIR /app

COPY . .

RUN npm install

EXPOSE 4000
# required for docker desktop port mapping

CMD ["node", "app.js"]