FROM node:8
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY goodbye-world.js ./
CMD ["npm", "start"]
