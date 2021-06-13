FROM node:14.4.0

# アプリケーションディレクトリを作成する

WORKDIR /app/client
COPY package*.json ./
COPY yarn.lock ./
RUN yarn install

COPY . .

CMD ["npm", "start"]

EXPOSE 3000
