FROM mjgargani/puppeteer:trybe1.0

COPY /e2e ./e2e

EXPOSE 3001
ADD node_modules.tar.gz ./
ENTRYPOINT npm test
