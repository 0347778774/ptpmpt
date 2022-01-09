FROM node:latest
WORKDIR /client
COPY package.json /client
RUN yarn install
COPY . .
CMD ["yarn","run", "start"]