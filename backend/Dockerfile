FROM node:24

WORKDIR /app

COPY backend/package*.json ./

RUN npm install --production

COPY backend/ .

EXPOSE 8000

CMD ["npm", "start"]