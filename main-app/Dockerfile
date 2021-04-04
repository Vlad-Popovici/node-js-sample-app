FROM node:12.22.0-alpine3.11

WORKDIR /main-app

RUN npm install

COPY . /main-app

EXPOSE 8000

CMD ["node", "main.js"]
