FROM node:14.16.0-alpine3.10

WORKDIR /login-app

RUN npm install

COPY . /login-app

EXPOSE 8000

CMD ["node", "login.js"]
