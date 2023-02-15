FROM node:14-alpine
WORKDIR /app
ADD ./node_modules.tar.gz .
COPY . ./app
ENTRYPOINT [ "npm", "start" ]