FROM node:14.4.0-slim

# アプリケーションディレクトリを作成する

WORKDIR /app/client
COPY package*.json ./
COPY yarn.lock ./
RUN yarn install

COPY . .

EXPOSE 3000
CMD ["npm", "start"]
