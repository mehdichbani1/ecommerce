FROM node:19-alpine

WORKDIR /.
COPY package*.json ./
RUN npm install
COPY ./ ./
EXPOSE 7000
CMD npm start