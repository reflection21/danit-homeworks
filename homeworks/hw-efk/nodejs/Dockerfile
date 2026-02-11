FROM node:20-alpine

WORKDIR /app

COPY package*.json ./

RUN npm install 

COPY . .

EXPOSE 10000

ENTRYPOINT ["node"] 

CMD ["index.js"]