FROM node:16.14.2-alpine3.15

RUN apk update

ENV TZ Asia/Tokyo
ENV PATH $HOME/.yarn/bin:$HOME/.config/yarn/global/node_modules/.bin:$PATH

WORKDIR /app

CMD ["npm", "run", "dev"]
