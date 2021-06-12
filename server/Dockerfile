FROM node:14.4.0-slim

# アプリケーションディレクトリを作成する

WORKDIR /app/server
COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 4000
CMD ["npm", "start"]
