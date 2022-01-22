FROM mjgargani/puppeteer:trybe1.0 AS build
WORKDIR /app/tests
ADD node_modules.tar.gz /app/tests/
COPY . .
CMD ["npm", "test"]