FROM node:12
WORKDIR /var/www/api
COPY ./package.json .
RUN yarn
CMD ["yarn", "start"]
EXPOSE 3333
