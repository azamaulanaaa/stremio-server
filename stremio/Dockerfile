FROM node:14.15.0-alpine

WORKDIR /stremio

ARG VERSION=4.4.142

RUN apk add --no-cache wget ffmpeg

COPY . .

EXPOSE 11470

CMD [ "node", "server.js"]
