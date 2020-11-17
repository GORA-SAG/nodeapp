FROM node:8

WORKDIR /usr/src/app

RUN npm ci --only=production

EXPOSE 8080
CMD [ "npm", "start" ]