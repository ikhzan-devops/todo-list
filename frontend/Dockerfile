FROM node:25-alpine

ENV VUE_APP_API_URL=http://todo-backend:8080


WORKDIR /app

COPY . .

RUN yarn install

CMD ["yarn", "serve"]
