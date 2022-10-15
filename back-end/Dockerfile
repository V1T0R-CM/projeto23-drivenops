FROM node:16

WORKDIR /usr/src/

COPY . .

RUN npm i
RUN NPM RUN BUILD

EXPOSE 5000

CMD [ "npm", "start" ]