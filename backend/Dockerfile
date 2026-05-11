FROM node:18-alpine
#testeo pipeliness

WORKDIR /app

COPY package*.json ./

RUN npm install --production

COPY . .

EXPOSE 3001

CMD ["npm", "start"]
