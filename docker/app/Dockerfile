FROM mhart/alpine-node:12

ENV NODE_ENV="development"

WORKDIR /app
COPY . .

RUN yarn install

CMD ["yarn", "start"]