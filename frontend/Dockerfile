FROM node:18.16.1-alpine3.18

RUN mkdir --p /app && chown -R node:node /app
WORKDIR /app

EXPOSE 3000
CMD echo 1; npm install; echo 2; npm run start