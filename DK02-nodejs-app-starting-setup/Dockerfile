

FROM node

WORKDIR /app
# we just copy package.json before installing
# if you change juste the code, the build process will use a cached npm install
# faster, no need to install the package again unnecessarly 
COPY package.json /app 

RUN npm install

COPY . /app

EXPOSE 80

CMD ["node", "server.js"]