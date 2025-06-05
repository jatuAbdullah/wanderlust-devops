FROM node:21

WORKDIR /app

COPY . .

RUN npm i

RUN npm run test

COPY .env.sample .env

EXPOSE 5000

CMD ["npm","start"]


