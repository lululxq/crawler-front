FROM node:lts

WORKDIR /app

COPY web/ .

RUN yarn config set registry https://registry.npm.taobao.org/
RUN yarn install

CMD ["yarn", "serve"]