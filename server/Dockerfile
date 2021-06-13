FROM node:14.4.0

# アプリケーションディレクトリを作成する

WORKDIR /app/server
COPY package*.json ./
RUN npm install

COPY . .

CMD ["npm", "start"]

EXPOSE 4000
