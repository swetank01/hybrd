FROM node:14-alpine

WORKDIR /frontend
RUN echo "Branch name: "
COPY ./src/client/package.json ./
RUN yarn
RUN yarn cache clean
