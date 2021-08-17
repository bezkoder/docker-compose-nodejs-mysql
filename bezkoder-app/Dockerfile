FROM node:14

WORKDIR /bezkoder-app
COPY package.json .
RUN npm install
COPY . .
CMD npm start
