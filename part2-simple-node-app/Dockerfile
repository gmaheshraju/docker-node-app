FROM node:14

WORKDIR /usr/src/app

COPY . .
# COPY package*.json ./
# COPY tsconfig.json ./
RUN npm install



RUN npm build

CMD ["npm", "start"]

EXPOSE 3004
