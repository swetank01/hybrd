FROM node:14-alpine

WORKDIR /frontend

COPY ./src/client/package.json ./
RUN yarn
RUN yarn cache clean
