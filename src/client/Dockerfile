ARG TAG

FROM swetank01/react-cache:$TAG as builder

WORKDIR /frontend

COPY . .

RUN yarn
RUN yarn dev