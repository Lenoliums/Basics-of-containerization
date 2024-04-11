FROM node:14

WORKDIR /lena-app
COPY package.json .
RUN npm install
COPY . .
CMD npm start
