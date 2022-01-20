FROM mjgargani/puppeteer:trybe1.0 AS build
WORKDIR /app/tests
COPY package*.json ./
RUN npm install
COPY . .
CMD  ["npm", "test"]