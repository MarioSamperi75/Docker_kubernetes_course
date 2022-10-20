FROM node:14

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=mario
ENV MONGODB_PASSWORD=123456

CMD ["npm", "start"]