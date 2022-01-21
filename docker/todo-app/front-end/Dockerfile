FROM node:14-alpine AS build
WORKDIR /app/front-end
ADD node_modules.tar.gz /app/
COPY . .
EXPOSE 3000
ENTRYPOINT npm start