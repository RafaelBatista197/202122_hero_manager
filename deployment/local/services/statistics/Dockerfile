FROM node


WORKDIR /app/services/statisitcs

COPY package.json .

RUN npm install
RUN npm install -g nodemon

ENTRYPOINT [ "nodemon", "src/index.js"]