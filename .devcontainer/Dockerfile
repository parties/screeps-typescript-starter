FROM node:12-alpine

ARG SCREEPS_TOKEN
ENV SCREEPS_TOKEN=$SCREEPS_TOKEN

RUN apk add --update --no-cache git ca-certificates openssl openssh
RUN npm install -g rollup
