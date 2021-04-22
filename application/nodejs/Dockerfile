# BASE IMAGE
FROM node:alpine
WORKDIR /usr/app
# ADD ENTRYPOINT

COPY ./package.json ./
RUN npm install -g npm@7.10.0
COPY ./ ./

CMD ["npm", "start"]