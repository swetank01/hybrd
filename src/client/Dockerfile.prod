ARG TAG

FROM swetank01/react-cache:$TAG as builder

WORKDIR /frontend

COPY . .

RUN yarn
RUN yarn build

# base image 
FROM nginx:1.16.0-alpine

# copy artifact build from the 'build environment'
COPY --from=builder /frontend/build /usr/share/nginx/html

ENV PORT=80
EXPOSE 80