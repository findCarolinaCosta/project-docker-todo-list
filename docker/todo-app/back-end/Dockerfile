FROM node:14-alpine AS build
WORKDIR /app/back-end
ADD node_modules.tar.gz /app/
COPY . .
EXPOSE 3001
ENTRYPOINT ["npm", "start"]