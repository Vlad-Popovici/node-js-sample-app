FROM node:15.13.0-alpine3.10

WORKDIR /cart-app

RUN npm install

COPY . /cart-app

EXPOSE 8000

CMD ["node", "cart.js"]
