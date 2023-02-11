FROM node:14-alpine

WORKDIR /frontend

COPY ./src/client/package.json ./
RUN echo "cache test 1"
RUN yarn
RUN yarn cache clean
