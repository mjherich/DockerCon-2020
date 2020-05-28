FROM node:12

WORKDIR /code

COPY src/package.json /code/package.json

RUN npm install

COPY src /code

EXPOSE 3000

CMD [ "npm", "run", "start" ]
