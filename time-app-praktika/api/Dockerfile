FROM node:alpine

WORKDIR /time-app

COPY package*.json .

RUN npm install

COPY . .

EXPOSE 7942

CMD ["npm", "run", "dev"]