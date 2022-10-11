FROM node:14

COPY ["/src", "./src"]

EXPOSE 3001
ADD node_modules.tar.gz ./
ENTRYPOINT ["npm", "start"]
