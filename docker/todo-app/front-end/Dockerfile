FROM node:14

WORKDIR /app
COPY /src ./src

EXPOSE 3001
ADD node_modules.tar.gz ./
ENTRYPOINT ["npm", "start"]
