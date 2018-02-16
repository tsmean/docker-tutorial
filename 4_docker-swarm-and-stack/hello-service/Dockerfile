FROM node:8
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY hello-world.js ./
CMD ["npm", "start"]
