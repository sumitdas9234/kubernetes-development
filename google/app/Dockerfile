FROM node:14-alpine

# Create app directory
WORKDIR /usr/src/app

# Bundle app source
COPY dist .

EXPOSE 8000
CMD [ "node", "api.bundle.js" ]
