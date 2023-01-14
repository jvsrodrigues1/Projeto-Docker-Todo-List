FROM node:14-alpine

EXPOSE 3000

WORKDIR /front-end

COPY ./package.json .

RUN npm install

ADD ./node_modules.tar.gz .

COPY . .

ENTRYPOINT ["npm", "start"]
