FROM node:20-alpine

ENV APP=/usr/src/app

WORKDIR ${APP}

COPY public/ ${APP}/public

COPY src/ ${APP}/src

COPY package*.json ${APP}

RUN npm install --production

CMD ["npm", "start"]