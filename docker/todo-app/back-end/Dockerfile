FROM node:14-alpine

EXPOSE 3001

WORKDIR /back-end

COPY ./package.json .

RUN npm install

ADD ./node_modules.tar.gz .

COPY . .

ENTRYPOINT ["npm", "start"]