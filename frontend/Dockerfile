FROM node:16-alpine

ENV BACKEND_URL=http://backend:5050/api

ADD . /app

WORKDIR /app

RUN npm install

ENTRYPOINT [ "npm" ]

CMD [ "start" ]
