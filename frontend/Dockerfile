FROM node:14

WORKDIR /app

COPY ./dist /app

RUN npm i -g serve

RUN npm install --production

EXPOSE 5000

CMD ["serve", "-s", "dist", "-p", "5000"]