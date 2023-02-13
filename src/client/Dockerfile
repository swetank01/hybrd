ARG TAG

FROM swetank01/react-cache:$TAG as builder

WORKDIR /frontend

COPY . .

RUN yarn

CMD ["yarn start"]
EXPOSE 3000