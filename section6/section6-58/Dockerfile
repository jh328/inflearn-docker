# apline = 최적화된 작은 이미지 (현업에서 실제 많이 사용)
FROM node:20-apline

WORKDIR /app

COPY . .

RUN npm install

RUN npm run build

EXPOSE 3000

ENTRYPOINT ["npm", "run", "start"]