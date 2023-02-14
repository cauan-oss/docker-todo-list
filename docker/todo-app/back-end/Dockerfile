FROM node:14-alpine
WORKDIR /
ADD ./node_modules.tar.gz .
COPY . .
ENTRYPOINT [ "npm", "start" ]