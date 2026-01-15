FROM oven/bun:1.1-alpine

WORKDIR /app

COPY package*.json bun.lock ./

RUN bun install

EXPOSE 3000

COPY . /app

CMD ["bun", "run", "dev"]