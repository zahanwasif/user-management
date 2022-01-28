FROM node:14.18.3
WORKDIR /usr/src/app

COPY ["package.json", "yarn.lock", "./"]

RUN yarn install

COPY . .

EXPOSE ${PORT}

CMD [ "yarn", "start" ]