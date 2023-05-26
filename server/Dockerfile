FROM node:16-alpine
WORKDIR /usr/api
COPY package*.json ./

RUN npm install
COPY . .

EXPOSE 3009

CMD ["npm", "start"]