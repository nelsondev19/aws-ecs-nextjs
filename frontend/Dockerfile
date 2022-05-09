FROM node:14

WORKDIR /app

COPY . /app

ENV NODE_ENV=production

RUN npm i -g serve

RUN npm install --production

EXPOSE 5000

CMD ["npm", "run", "serve"]