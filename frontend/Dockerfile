FROM node:22-alpine

WORKDIR /app

COPY package*.json .

RUN npm install

EXPOSE 4000

COPY . /app

CMD ["npm", "run", "dev", "--", "--host"]