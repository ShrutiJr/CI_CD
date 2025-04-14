FROM node:14-alpine3.12
WORKDIR /app
COPY package*.json ./
RUN cd backend && npm install
COPY . .
EXPOSE 4000
CMD ["node","backend/index.js"]
