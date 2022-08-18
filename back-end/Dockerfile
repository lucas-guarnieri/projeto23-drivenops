FROM node

WORKDIR /usr/back-end/src/

COPY . .

RUN npm i
RUN npm run build

EXPOSE 5000

CMD [ "npm", "start" ]